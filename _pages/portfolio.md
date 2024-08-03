---
layout: archive
title: "Art Portfolio"
permalink: /portfolio/
author_profile: true
---

Welcome to my art portfolio! I'm a passionate wildlife enthusiast and a self-taught artist. My love for nature, particularly bird watching, has inspired many of my creative projects. 

I ventured into bird photography this year with the name "ScrubJ Photography" as I go birding a few times per month. Alongside photography, I specialize in colored pencil drawings and watercolor paintings.

In addition to my wildlife-inspired art, I blend my academic interests with art. I sometimes illustrate scientific concepts, particularly for my own research in neuroscience. This also includes creating thesis defense posters for my colleagues. 

I hope you find inspiration and joy in exploring my art as much as I have in creating it!

{% include base_path %}

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
