---
widget: portfolio

headless: true

weight: 60

title: Projects
subtitle: ''

content:
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  filter_button:
    - name: All
      tag: '*'
    - name: Research
      tag: Research
    - name: ComDev
      tag: ComDev

design:
  columns: '2'
  spacing:
    padding: ["15px", "0", "15px", "0"]

  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   5 = Showcase
  view: 3

  flip_alt_rows: false
---
<iframe seamless = "" width = "100%", height = "500" class="shortcode-iframe" src="/leaflet/work_map.html"></iframe>