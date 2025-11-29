---
layout: page
title: About
permalink: /about/
weight: 3
---

<style>
.name-display {
  font-size: 2.5em !important; /* Makes name bigger */
  display: inline-block;
  overflow: hidden;
  white-space: nowrap;
  border-right: 3px solid #333;
  animation: typing 3s steps(20, end), blink-caret 0.75s step-end infinite;
  font-family: monospace;
}

@keyframes typing {
  from { width: 0; }
  to { width: 100%; }
}

@keyframes blink-caret {
  from, to { border-color: transparent; }
  50% { border-color: #333; }
}
</style>

# **About Me**

Hi I am <span class="name-display">Tilemachos Tsakiris</span> :wave:,<br>
I am an IT enthusiast exploring networking, systems administration, and virtualization. [web:1][web:4]

I enjoy learning new technologies, building projects, and improving my skills every day.  

Some of my interests include:
- Home lab setups and network configurations
- Docker and containerized projects
- Raspberry Pi experiments and small automation projects

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
