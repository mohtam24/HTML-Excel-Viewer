# Repository Guidelines

This repository stores an Excel file and generated HTML views. When updating or adding code, keep the following guidelines in mind:

- Use **two spaces** for indentation in both HTML and Python files.
- Prefer plain Python 3 without external dependencies when parsing the spreadsheet.
- HTML pages should have UTF-8 encoding and minimal CSS.
- Group property sets using `<details>` and `<summary>` tags so they can be collapsed.
- Each commit should include a short summary of the changes made.
- After modifications, run the following command to make sure the Excel file is readable:
  ```bash
  python3 - <<'PY'
  import zipfile, xml.etree.ElementTree as ET
  print(len(zipfile.ZipFile('Excel für codex.xlsx').namelist()))
  PY
  ```
