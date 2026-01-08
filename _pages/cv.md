---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **M.S. in Photoelectric Information Engineering**, University of Chinese Academy of Sciences (UCAS), Beijing, China, 2027 (Expected)
  * *Research Unit:* Shanghai Institute of Optics and Fine Mechanics (SIOM)
  * *Advisor:* Prof. Guohai Situ
* **B.S. in Process Equipment and Control Engineering**, Changzhou University (CZU), Changzhou, China, 2023

Research Experience
======
* **Graduate Research Assistant**
  * *Computational Optical Imaging Group, SIOM, CAS*
  * *2024 – Present*
  * **Single-Pixel Imaging (SPI) System:** Developing a high-speed SPI system using a rotating disk. Conducted physical modeling and simulation of optical defocus and motion blur. Implemented hardware control for precise motor modulation.
  * **Scattering Imaging:** Researching image reconstruction through scattering media (e.g., smoke/fog). Successfully deployed UNet-based restoration models on edge devices (NVIDIA Jetson Orin Nano) using ONNX and TensorRT optimization for real-time inference.
  * **Simulation & Algorithms:** Utilized Python (PyTorch, NumPy) for end-to-end simulation of optical wave propagation (Fourier optics) and deep learning-based inverse problem solving.

Skills
======
* **Programming & Tools:** Python (Advanced), MATLAB, C++, LaTeX, Git
* **Deep Learning:** PyTorch, OpenCV, TensorRT, ONNX, BasicSR
* **Optical Engineering:** Physical Optics Modeling, Fourier Optics, Light Field Simulation, Hardware Control (Servo/Motor)
* **Languages:** Chinese (Native), English (Professional Working Proficiency)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and Academic Activities
======
* Member of the Computational Optical Imaging Group at SIOM.
* Active contributor to open-source optical simulation projects (if applicable).
