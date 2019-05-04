---
layout: single
author_profile: true
title: ""
---

{% include toc icon="gears" title="Table of Contents" %}

# Background

<p style="text-align: center;">"Nature is showing us only the tail of the lion..." - Albert Einstein </p>

## Current Position 

Chemical Engineer \\
[Chemical Informatics Research Group](https://www.nist.gov/mml/csd/chemical-informatics-research-group) \\
Chemical Sciences Division \\
Material Measurement Laboratory \\
National Institute of Standards and Technology \\
100 Bureau Drive STOP 8320 \\
Gaithersburg, MD 20899-8320 USA \\
\\
E: [nathan.mahynski@nist.gov](mailto: nathan.mahynski@nist.gov) \\
T: (301) 975-6836

[CV](https://drive.google.com/file/d/0B6sFx4ruP0--R2lHcWZmWWV5d3c/view){: .btn .btn--success}

## Education

* Ph.D., Chemical Engineering, Princeton University, 2015
  Certificate in Computational and Information Science
* M.A., Chemical Engineering, Princeton University, 2012
* B.S., Chemical Engineering, Purdue University, 2010 (Magna Cum Laude)

## Recent Awards

* Election to Sigma Xi, 2017
* Univ. of Washington Distinguished Young Scholar in Chemical Engineering, 2016
* Christopher J. Wormald Prize in Thermodynamics, 2015

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

