---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a PhD Candidate in **Human-Robot Interaction (HRI)** at Grenoble Alpes Université (France), within GIPSA-Lab, LIG and LPNC. My research sits at the intersection of **Natural Language Processing** and **Robotics**, with a specific focus on making autonomous systems more intuitive to control.

Currently, I am working on **VoiceStick**: a project dedicated to replacing traditional joysticks with spontaneous voice commands for drone navigation. By analyzing how humans naturally give directions, I develop real-time pipelines that allow UAVs to understand and execute complex maneuvers with "human-like" reaction times.

My work involves:
* **Spontaneous Speech Analysis:** Capturing and processing how we actually speak in high-stakes environments.
* **Robot Learning:** Training models to map vocal intentions to agile flight trajectories.
* **Real-time Systems:** Integrating MoCap data and deep learning models for seamless, low-latency execution.

I am in the final year of my PhD (expected defense in **November 2026**) and I am actively looking for opportunities where I can apply my expertise in AI and robotics to create the next generation of interactive autonomous systems.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Interspeech 2026</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  [XXX](https://rhiawenoid.github.io/VoiceStick-Research/)

  **A. Henry**, C. Graff, S. Rossato, et al

  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
  </div>
</div>

- [Guiding a Drone by Voice: Corpus of Spontaneous Speech and Processing Pipeline with Human-Like Reaction-Time](https://github.com), **A. Henry**, C. Graff, S. Rossato, et al, **LREC 2026**
- [Guiding sightless people one dimension at a time: how the strategy used in spontaneous voice instructions benefits sonification-based guidance](https://github.com), C. Fons, **A. Henry**, S. Huet, et al, **PLOS ONE**
- [Voice Commands for Guidance to a 3D Position: To Collect Spontaneous Data](https://github.com), **A. Henry**, C. Graff, S. Rossato, et al, **PETRA 2025**

# 📖 Educations
- *Nov. 2023 -- Nov 2026 (now)*, PhD in Human-Robot Interaction, Univ. Grenoble Alpes, Grenoble, France
- *Sep. 2021 -- Aug 2023 (now)*, MSc in Computer Science focus in Artificial Intelligence, Univ. Le Mans, Le Mans, France

# 💼 Experience
- *Nov. 2023 -- Nov. 2026*, **PhD Researcher**, Univ. Grenoble Alpes, Grenoble, France
  - Developed a real-time spontaneous speech command system for drone navigation  
  - Engineered a novel hybrid architecture combining LSTM and Attention mechanisms to handle spontaneous speech
  - Analyzed human cognitive strategies in spatial guidance to inform model design
  - Developed a Mixed-Reality experimental setup bridging real-world drone telemetry with a constrained virtual view in Unreal Engine

- *Nov. 2023 -- Nov. 2026*, **Graduate Teaching Assistant**, Univ. Grenoble Alpes, France
  - Courses taught: Computer Vision, Artificial Intelligence, C Programming, Algorithms
  - Delivered technical lectures and led lab sessions for multiple groups of ∼30 undergraduate students
  - Supervised practical assignments and coding exercises

- *Apr. 2022 -- Sep. 2023*, **Robotics Software Engineer (Apprenticeship)**, Apside Top, Le Mans, France
  - Engineered an autonomous robot on Nvidia Jetson Nano capable of real-time human tracking and following
  - Implemented Visual Odometry algorithms for camera-only localization and "return-to-home" features
  - Optimized the entire processing pipeline using multiprocessing to ensure low-latency inference on edge hardware
  - Built custom datasets and trained PyTorch models for obstacle detection and navigation