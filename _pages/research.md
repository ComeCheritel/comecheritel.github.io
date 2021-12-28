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
<ul>{% select 2021_04_SCC_EGU in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
{%- assign U_SCC = site.publications | where: 'uncertainty_SCC', true -%}
{%- for U_SCC in site.publications -%}
  {% include archive-single-cv.html %}
  {{- publication.title -}}
{%- endfor -%}

{%- assign fp = site.posts | where: 'featuredPost', true -%}
{%- for fp in site.posts -%}
  {{- post.title -}}
{%- endfor -%}

Impact of the age structure and population dynamics on carbon emissions
======


Integrating endogenous population dynamics in climate-economics scenarios
======

Related publications
----
<ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>


  


