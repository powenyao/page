---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

My main area of research is **User Interface and User Interaction in Extended Reality**
Primarily, it manifests in my work on the Virtual Equipment System. I have dabbled a bit into **Artificial Intelligence, Machine Learning, Computer Vision** I also dabbled a bit in **Text Entry**

<!--(Links to pdf will be added after checking authors rights)-->
<!--<i class="fa-regular fa-file"></i>-->

Virtual Equipment System
* <a href="https://doi.org/10.1007/978-3-030-50729-9_19">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a> 
  Designing Virtual Equipment Systems for VR
* <a href="https://doi.org/10.1145/3385959.3421723">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Interfacing with sensory options using a Virtual Equipment System
* <a href="https://doi.org/10.1007/978-3-030-78642-7_48">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a> 
  Virtual Equipment System: expansion to address alternate contexts
* <a href="https://doi.org/10.1109/VRW52623.2021.00256">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Virtual Equipment System: Face Mask and Voodoo Doll for User Privacy and Self-Expression Options in Virtual Reality
* <a href="https://doi.org/10.1007/978-3-031-05939-1_9">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Virtual Equipment System: First Evaluation of Egocentric Virtual Equipment for Sensory Settings
* <a href="https://doi.org/10.1007/978-3-031-05939-1_8">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Virtual Equipment System: Toward Bag of Holding and Other Extradimensional Storage in Extended Reality
  

Machine Learning
* <a href="https://doi.org/10.1145/3485279.3485306">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Virtual equipment system: toward peripersonal equipment slots with machine learning
* <a href="https://doi.org/10.1145/3485279.348530">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Toward Using Machine Learning-Based Motion Gesture for 3D Text Input
* <a href="https://doi.org/10.1145/3485279.3485305">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Toward Predicting User Waist Location From VR Headset and Controllers Through Machine Learning
* <a href="10.1109/VRW55335.2022.00195">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Toward Using Multi-Modal Machine Learning for User Behavior Prediction in Simulated Smart Home for Extended Reality
* <a href="https://doi.org/10.1007/978-3-031-05939-1_7">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Using Multi-modal Machine Learning for User Behavior Prediction in Simulated Smart Home for Extended Reality


Text Entry
* <a href="https://doi.org/10.1145/3385959.34217">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Punch typing: Alternative method for text entry in virtual reality
* <a href="10.1109/VRW55335.2022.00295">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Flick Typing: Toward A New XR Text Input System Based on 3D Gestures and Machine Learning
* <a href="https://doi.org/10.1007/978-3-031-05939-1_26">
  <i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  Flick Typing: A New VR Text Input System Based on Space Gestures


{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
