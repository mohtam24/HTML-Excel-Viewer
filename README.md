# Style Anweisungen

diagram_style:
  layout: horizontal_tree # von links nach rechts
  root_node:
    label: "090_HOHLRAUMSICHERUNG"
    shape: circle
    background_color: "#4CB3E2"
    font_weight: bold
    font_size: 16px
    text_align: center
  node_categories:
    - name: "Objekt"
      label_prefix: "100_Objekt"
      color: "#C6EBAF"
      border_color: "#77C27B"
    - name: "Merkmal Objekt"
      label_prefix: "Merkmal 100_Objekt"
      color: "#DDE6FB"
      border_color: "#7A9DE2"
    - name: "Teilobjekt"
      label_prefix: "110_Teilobjekt"
      color: "#C6EBAF"
      border_color: "#77C27B"
    - name: "Merkmal Teilobjekt"
      label_prefix: "Merkmal 110_Teilobjekt"
      color: "#DDE6FB"
      border_color: "#7A9DE2"
  edges:
    style: solid
    color: "#3F3F3F"
    arrow: none
  node_shape: rounded_rectangle
  font_family: sans-serif
  default_font_size: 14px
  placeholder_images:
    - "Spiesschirm": "[Bild_Spiesschirm]"
    - "Lastverteilerschiene": "[Bild_Lastverteilerschiene]"
    - "Vorpflandblech": "[Bild_Vorpflandblech]"
    - "Rohrschirm": "[Bild_Rohrschirm]"
    - "Leibung": "[Bild_Leibung]"
