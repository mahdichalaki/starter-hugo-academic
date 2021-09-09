---
title: Example Project
summary: Identification and Control of a Beam's Vibrations

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

In this experiment, a beam has been attached to a shaker and an IMU sensor has been used to measure and record the linear acceleration of the beam's free end.
By investigating and analyzing IMU data in the frequency domain, a linear transfer function has been approximated which described systems dynamics. (In this part, MATLAB 'frf' and 'fitmag' functions were used)

Here, the system input is the voltage applied to a piezoelectric actuator and the output is the accelerometer's data. (both acceleration and position are available through integrating)

In the next part, by employing several Matlab toolboxes, a PID controller has been designed to attenuate the beam's vibration by adjusting the piezoelectric voltage.

Controllers have been designed using SISO Tools and Simulink PID Block built-in functions. Effects of changing controller gains and time constant have been investigated too.

Some of the plots used for evaluating and observing system behaviors used in this project include Root-Locus, Bode, time domain response, and Nyquist.
