---
permalink: /homesplash/
title: "Welcome"
header:
  image: /assets/images/header.png
layout: splash
classes:
  - landing
---

<p><img src="/assets/images/photoAdelstein.jpg" alt="photo of Prof Adelstein" width="100"/> 
Nicole Adelstein has a Ph.D. in Materials Science and Engineering from UC Berkeley. Her undergraduate BA degree was in Interdisciplinary Chemistry and Physics from Reed College. She was at Lawrence Livermore National Laboratory for three years as a postdoc until starting at San Francisco State University (SFSU).  </p>

The Adelstein Research Group seeks to understand and improve materials for electrochemical technologies, with a focus on Li-ion batteries. We study atomic-scale processes, such as diffusion, in battery materials, using first-principles (quantum mechanics) simulations.

## Current Members ##
{% for member in site.data.members.current %}
* {{ member.name }} ({{ member.date }})
{% endfor %}

## Former Members ##
{% for member in site.data.members.former %}
* {{ member.name }} ({{ member.date }})
{% endfor %}

## Summer Students ##
{% for member in site.data.members.summer %}
* {{ member.name }} ({{ member.date }})
{% endfor %}

