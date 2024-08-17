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

(Links to pdf will be added after checking authors rights)

Virtual Equipment System
* Designing Virtual Equipment Systems for VR
* Interfacing with sensory options using a Virtual Equipment System
* Virtual Equipment System: expansion to address alternate contexts
* Virtual Equipment System: Face Mask and Voodoo Doll for User Privacy and Self-Expression Options in Virtual Reality
* Virtual Equipment System: First Evaluation of Egocentric Virtual Equipment for Sensory Settings
* Virtual Equipment System: Toward Bag of Holding and Other Extradimensional Storage in Extended Reality

Machine Learning
* Virtual equipment system: toward peripersonal equipment slots with machine learning
* Toward Using Machine Learning-Based Motion Gesture for 3D Text Input
* Toward Predicting User Waist Location From VR Headset and Controllers Through Machine Learning
* Toward Using Multi-Modal Machine Learning for User Behavior Prediction in Simulated Smart Home for Extended Reality
* Using Multi-modal Machine Learning for User Behavior Prediction in Simulated Smart Home for Extended Reality

Text Entry
* Punch typing: Alternative method for text entry in virtual reality
* Flick Typing: Toward A New XR Text Input System Based on 3D Gestures and Machine Learning
* Flick Typing: A New VR Text Input System Based on Space Gestures

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
