---
permalink: /
title: "Homepage"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an undergraduate student @ Yonsei University, majoring in physics and electrical & electronic engineering. I am currently studying machine learning and computer vision with the goal of entering a combined MS–PhD program in the spring of 2027.

In particular, I am interested in neural network compression (e.g., network quantization) and physical AI in the context of low power devices, as well as diffusion models motivated by a strong interest in mathematics.

{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}
