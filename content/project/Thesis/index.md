---
title: B.Sc. Thesis Project
summary: Fault detection of a centrifugal pump using a CNN network
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
slides: Thesis
---

In this project, I tried to design and build a monitoring system that detects centrifugal pump's faults using vibrational signals. 

This system consists of two parts: A device which is installed on the discharge side of the pump, and a centeral processing part. Former device samples vibrational data and sends it to the cloud processing device. There, data will be prepreprocessed and sent into a Deep Convlolutional Neural Network. This system is also able to find out if the emerging fault is of a new type and add it to its directory.

In this project, I was responsible for designing the network architecture, data collection for model training, and designing a compact enclosure for the portable device. 
