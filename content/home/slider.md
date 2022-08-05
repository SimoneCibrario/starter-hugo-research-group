---
widget: slider  # Use the Slider widget as this page section
weight: 20  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: 200px
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Play and players
      content: 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: coders.jpg
        fit: contain
    - title: Play and objects
      content: 
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: contact.jpg
        fit: contain
    - title: Play and nonhumans
      content: 
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: welcome.jpg
        fit: contain
---
