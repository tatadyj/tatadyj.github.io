---
layout: single
author_profile: true
title: ""
---

# Background

My name is Yajun Ding. I am a data scientist at [SMS ASSIST](https://www.smsassist.com). My background is in computational thermodynamics and my research focuses on three principal areas:

1. Using statistical mechanical methods to develop efficient computational methodologies for computing thermodynamic properties of fluids.
2. Understanding and controlling colloidal crystal self-assembly and polymorphism.
3. Mathematical and computational modeling of infecious diseases and epidemiology of HIV. \\
More information about active research projects and objectives is available [here](https://tatadyj.github.io/_research/research/).

## Curriculum Vitae and Resume 

[CV](https://drive.google.com/file/d/1q-P4iBNW7E5S2st4kl_GNcdS-eU53mzY/view?usp=sharing){: .btn .btn--success}
[Resume](view){: .btn .btn--success}

## Education

* Ph.D., Chemical Engineering, Lehigh University, 2015
* M.S., Chemical and Biomolecular Engineering, University of Pennsylvania, 2010
* B.S., Chemical and Biological Engineering, China Agricultural University, 2006

## Recent Awards

* Gotshall Fellowship, Lehigh University, 2012
* Baldwin Fellowship, Lehigh University, 2010

---

# Recent Press

{% include group-by-array collection=site.posts field="categories" %}

{% for category in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ category | slugify }}" class="archive__subtitle">{{ category }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

