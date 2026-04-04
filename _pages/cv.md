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
* M.S. in Computer Science and Technology, Central South University, 09/2022 - 06/2025
  * Advisor: Prof. Min Li
* B.S. in Computer Science and Technology, Central South University, 09/2019 - 06/2022
* Undergraduate studies in Geophysics, Central South University, 09/2018 - 07/2019

Research experience
======
* Graduate Researcher, School of Computer Science and Engineering, Central South University, 08/2023 - 08/2025
  * MoChat: Joints-Grouped Spatio-Temporal Grounding Multimodal Large Language Model for Multi-Turn Motion Comprehension and Description
  * Published in IEEE Journal of Biomedical and Health Informatics, 30(3), 1972-1985.
  * Designed the skeleton representation pipeline and encoder architecture; processed NTU RGB+D videos and generated annotations with CogVLM.
  * Improved the skeleton encoder with a temporal regression module for spatio-temporal localization and motion description.

* Research Intern, Affective Intelligence and Ubiquitous Computing Research Center, Shenzhen, 09/2021 - 06/2022
  * Worked on multimodal depression recognition from EEG and speech.
  * Preprocessed the MODMA dataset with MATLAB and OpenSMILE and evaluated multiple classical machine learning models.
  * Applied dynamic classifier selection and achieved 97.6% accuracy in the best setting.

Engineering projects
======
* Motion Analysis Platform
  * Built skeleton and point-cloud visualization with Plotly and a multimodal LLM interface with Gradio.

* Multimodal Data Collection Platform
  * Developed a Vue3 + Vant + Spring Boot + MyBatis Plus + MySQL system for multimodal data collection and management.

* Android Health Assistant
  * Built a Unity + GLM4V application for photo-based health suggestions.

Current research direction
======
* Exploring embodied intelligence for VR-based agents, with a current focus on multimodal perception, tool use, and simulation-oriented interaction. 

Skills History
======
* Machine Learning / Deep Learning: PyTorch, OpenCV, Transformers
* Full-stack Web: Vue3, Vant, Gradio, Spring Boot, MyBatis Plus, MySQL
* 3D Graphics: Unity, Unreal Engine, Blender
* Others: Linux, Docker, Qt, Android (Java), ESP32

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
