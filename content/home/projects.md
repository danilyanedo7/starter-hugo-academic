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
    - name: Community Development
      tag: ComDev
    - name: Data Visualization
      tag: dataviz
    - name: R
      tag: R

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
