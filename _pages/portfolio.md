---
layout: archive
title: "Art Portfolio"
permalink: /portfolio/
author_profile: true
---

Welcome to my art portfolio! I'm a passionate wildlife enthusiast and a self-taught artist. My love for nature, particularly bird watching, has inspired many of my creative projects. I write for _the Callifornia Tech_ Wildlife Column and report on the campus ecology. Check my writings [here](https://tech.caltech.edu/authors/jieyu-zheng/).  

I ventured into wildlife photography in 2024 with the nickname "ScrubJ". Alongside photography, I specialize in colored pencil drawings and watercolor paintings. Check out this [short essay](https://localnewspasadena.com/2024/autumn-and-the-swan-whisperer/) about my art.

I also blend my academic interests with art, making illustrations of scientific concepts, particularly for my own research in neuroscience. This also includes creating thesis defense posters for my colleagues. 

I hope you find inspiration and joy in exploring my art as much as I have in creating it!

{% include base_path %}

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
