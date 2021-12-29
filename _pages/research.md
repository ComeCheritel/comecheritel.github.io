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

Cost-benefit integrated assessment models (IAMs) include a simplified representation of both the anthropogenic and natural components of the Earth system, and of the interactions and feedbacks between them. As such, they embed economic- and physics-based equations, and the uncertainty in one domain will inevitably affect the other. Most often, however, the physical uncertainty is explored by testing the sensitivity of the optimal mitigation pathway to a few key physical parameters; but for robust decision-making, the optimal pathway itself should ideally embed the uncertainty.
The goal of this project is, first, to propose a compact climate model that features climate uncertainty with a bayesian calibration. And second to propose a way to take this uncertainty into account for robust decision-making.

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
Coucou


Integrating endogenous population dynamics in climate-economics scenarios
======
Coucou

Related publications
----
<ul>
{%- assign endog_pop = site.publications | where: "endogenous_population", "true" -%}
{%- for post in endog_pop reversed-%}
  {% include archive-single-cv.html %}
{%- endfor -%}
</ul>


  


