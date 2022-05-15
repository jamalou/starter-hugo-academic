---
widget: eventcam
widget_id: event_cam
headless: true
weight: 30
title: Event-based Camera
subtitle: ""
active: true
design:
  columns: "2"
  background:
    text_color_light: false
    image_darken: 0
---
Event cameras are a new family of vision sensors that differ
completely from conventional cameras: instead of capturing
images at a fixed rate, they asynchronously measure per-pixel
brightness changes and output the event stream as a sequence
of tuples $[t, x, y, p]$ that encode the time $t$, pixel coordinates
$(x, y)$ and $p$ the sign of the brightness changes.