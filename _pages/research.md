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



Generational carbon accounts and the impact of the age structure and population dynamics on carbon emissions
======
Population aging and global warming are among the greatest challenges that humanity will face during the 21st century. Moreover, the characteristic time of persistence of greenhouse gases like CO2 in the atmosphere is of the same order as that of a human life. Thus, a certain emission also has consequences on future generations making global warming an intergenerational issue. From this point of view, the study of the influence of the age structure of the population as well as the identification of generational trends appears to be a particularly interesting issue. While the impact of population size and affluence on emissions has been extensively studied in an aggregated way, in particular with the IPAT identity framework, there is no scientific consensus concerning the impact of the age structure on carbon emissions. Indeed, it is conceivable that ageing will have an impact on an individual’s carbon footprint, as ageing leads to changes in behaviour and consumption practices, thus implying a change in energy consumption over the lifespan. Moreover, indirect effect of aging, such as household size shrinking may result in a variation in energy consumption. However, it is much more difficult to estimate whether this impact will be upwards or downwards.

The goal of this empirical project is to study the impact of the demographic structure and dynamics on carbon emissions in several countries. First, I would like to propose a breakdown of the carbon footprint by age group, a so-called Generational Carbon Accounts based on household budget survey micro-data and the use of input-out table. Then I would to disentangle age effects, generation effects and time trend which would allow an analysis of the impact of population aging on global warming.



Integrating endogenous population dynamics in climate-economics scenarios
======
In the scenarios considered in the economics and climate scientific community, population dynamics is fixed exogenously and is used as a driver for Integrated Assessment Models (IAMs). In particular, these models ignore the feedbacks of climate change on the economy, as well as on population dynamics. Furthermore, they cannot consider the effect of demographic deviation on the economy, since, population as well as GDP are the basis and cornerstone of these scenario: there is a potential huge methodological blindspot in the field of prospective modelling.

The goal of this project is thus to propose a framework that allow to propose scenarios that endogenously take into account the impact of climate change on population and on the economy.


Related publications
----
<ul>
{%- assign endog_pop = site.publications | where: "endogenous_population", "true" -%}
{%- for post in endog_pop reversed-%}
  {% include archive-single-cv.html %}
{%- endfor -%}
</ul>


  


