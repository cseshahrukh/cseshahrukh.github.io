---
permalink: /
title: "🌟 Hello there, I'm Shahrukh!"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<div style="text-align: justify; font-size: 14px;">
Welcome to my corner of the web! I'm Md Shahrukh Islam, a Ph.D. student and Graduate Research Assistant at the <a href="https://acyd.fiu.edu/">ACyD Lab</a>, <a href="https://www.fiu.edu/">Florida International University (FIU)</a>. Before joining FIU in August 2025, I worked as a software engineer at Samsung. I hold a B.Sc. in Computer Science and Engineering from Bangladesh University of Engineering and Technology (BUET). My journey in the tech world is driven by a deep curiosity and love for cutting-edge technologies, innovative solutions, and data-driven insights.
</div>


## 🔬 Research Interests
<div style="text-align: justify; font-size: 14px;">
At the <a href="https://acyd.fiu.edu/">ACyD Lab</a>, my research focuses on:
<ul>
  <li>Quantum computing</li>
  <li>Quantum computing and security</li>
  <li>Autonomous vehicle security</li>
  <li>Drone security</li>
  <li>Large language model (LLM) security</li>
</ul>
</div>


## 📄 Publications
<div style="text-align: justify; font-size: 14px;">
<ul>
{% for post in site.publications reversed %}
  <li>
    <a href="{{ post.url | relative_url }}"><strong>{{ post.title }}</strong></a><br>
    <i>{{ post.venue }}</i>, {{ post.date | date: "%Y" }}{% if post.paperurl %} · <a href="{{ post.paperurl }}">Paper</a>{% endif %}
  </li>
{% endfor %}
</ul>
See all on the <a href="{{ '/publications/' | relative_url }}">Publications</a> page.
</div>


## 🚀 A Bit About Me   
<div style="text-align: justify; font-size: 14px;">
Now based in <a href="https://www.google.com/maps/place/Miami,+FL,+USA">Miami, Florida</a>, I thrive on solving complex problems and creating impactful solutions. My professional experiences and academic pursuits have equipped me with a diverse skill set, ranging from full-stack development to machine learning and data analytics. I'm broadly interested in Systems, Networking, Security, Software Engineering and HCI.
</div>


## 🎯 What I Do 
<div style="text-align: justify; font-size: 14px;">  
Software Development: Crafting efficient and elegant code is my forte. I enjoy building scalable applications and exploring new frameworks.
Data Science: I have a keen interest in data, and I love extracting meaningful insights from complex datasets.
Technology Enthusiast: I stay updated with the latest trends and technologies, always eager to learn and adapt.
</div>

## 🌐 Let's Connect!  
<div style="text-align: justify; font-size: 14px;">
I'm always open to connecting with like-minded individuals, discussing innovative ideas, and exploring new opportunities. Feel free to reach out to me through the links provided, and let's create something amazing together!
</div>