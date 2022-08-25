---
widget: featured
title: LATEST ACTIVITIES
headless: true  # This file represents a page section.
weight: 50

# ... Put Your Section Options Here (title etc.) ...

content:
  columns: '1'
  # Page type to display. E.g. post, event, or publication.
  page_type: event
  # Choose how much pages you would like to display (0 = all pages)
  count: 1
  # Page order. Descending (desc) or ascending (asc) date.
  order: desc
  # Optionally filter posts by a taxonomy term.
  filters:
    tag: ''
    category: ''
    publication_type: ''
  archive:
    enable: true
    text: See all activities
    link: event/
design:
  # Toggle between the various page layout types.
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view:  card
  css_style: 
  css_class: 
  spacing:
      # Customize the section spacing. Order is top, right, bottom, left.
      padding: ["100px", "0", "100px", "0"]
  background:
    gradient_start: '#05257F'
    gradient_end: '#05257F'
    gradient_angle: 30
    # Text color (true=light, false=dark, or remove for the dynamic theme color).
    text_color_light: false
---