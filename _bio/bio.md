---
layout: single
author_profile: true
title: ""
---

{% include toc icon="gears" title="Table of Contents" %}

# Background

<p style="text-align: center;">"Nature is showing us only the tail of the lion..." - Albert Einstein </p>

## Current Position 

Data Scientist \\
[SMS ASSIST](https://www.smsassist.com) \\
Houston, TX \\
\\
E: [yding@smsassist.com](mailto: yding@smsassist.com) \\
T: (225) 456-6991

[CV](view){: .btn .btn--success}

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

