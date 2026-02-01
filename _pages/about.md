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

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).

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