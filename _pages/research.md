---
layout: archive
title: "Research projects"
permalink: /research/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}


Uncertainty and the Social Cost of Carbon
======

Related publications
----
<ul>
{%- assign U_SCC = site.publications | where: "uncertainty_SCC", "true" -%}
{%- for post in U_SCC -%}
  {% include archive-single-cv.html %}
  {{- post.title -}}
{%- endfor -%}
</ul>



Impact of the age structure and population dynamics on carbon emissions
======


Integrating endogenous population dynamics in climate-economics scenarios
======

Related publications
----
<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


  


