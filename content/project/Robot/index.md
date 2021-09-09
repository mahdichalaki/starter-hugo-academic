---
title: Designing and Building a four-legged robot
summary: Mechatronics course final project

date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  focal_point: Smart

links:
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

This project has been done as my Mechatronics course final project at the University of Tehran. In this project, a task had been assigned to each group (consisting of three students) to design, build and program a four-legged robot.

Our robot was designed to walk utilizing Chebyshev's Lambda mechanism. My groupmates had the responsibility of designing the mechanical parts of the robot (by SolidWorks) and analysing the mechanism (using SAM software) to check it before building different parts with wood and plexiglass.

In this project, I was responsible for programming the robot. I chose Arduino Uno as the microcontroller of the robot. I programmed it so it could move in four directions (it had two DC motors and one L298 driver) by using a joystick and stop if it faced a wall (I used SRF04 sensor).  
