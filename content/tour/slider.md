---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: _C. difficile_ clinical biology and ecology
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: microbes.jpg
    - title: Gut microbiome
      content: Severe disturbace in gut microbiome can lead to dysbiosis which has sever consequeces for the health of the host.  
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: gut.png
    - title: COVID-19 sequencing
      content: 'Just opened last month!'
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: covid.jpeg
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/
---
