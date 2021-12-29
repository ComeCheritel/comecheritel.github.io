---
layout: archive
title: "Research projects"
permalink: /research/
author_profile: true
redirect_from:
  - /projects
---

{% include base_path %}


Climate Uncertainty and the Social Cost of Carbon
======
With [Thomas Gasser](https://scholar.google.fr/citations?user=fjpNQPgAAAAJ&hl=en), [Armon Rezai](https://www.wu.ac.at/ecolecon/institute/team/arezai), [Artem Baklanov](https://www.hse.ru/en/org/persons/228998876) and [Michael Obersteiner](https://scholar.google.fr/citations?user=sl5sPKIAAAAJ&hl=en)


Related publications
----
<ul>
{%- assign U_SCC = site.publications | where: "uncertainty_SCC", "true" -%}
{%- for post in U_SCC reversed -%}
  {% include archive-single-cv.html %}
{%- endfor -%}
</ul>



Impact of the age structure and population dynamics on carbon emissions
======


Integrating endogenous population dynamics in climate-economics scenarios
======

Related publications
----
<ul>
{%- assign endog_pop = site.publications | where: "endogenous_population", "true" -%}
{%- for post in endog_pop reversed-%}
  {% include archive-single-cv.html %}
{%- endfor -%}
</ul>


  


