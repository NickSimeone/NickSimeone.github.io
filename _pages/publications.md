---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

- Spatial Analysis of Stream Temperature Response to Patterns of Land Cover and Stormwater Infrastructure – Master's Thesis Defense, UMBC, April 2025
- Evaluation of Watershed-Scale Impacts of Stormwater Infrastructure on Stream Temperature (Co-author) – AGU Fall Meeting, Washington, DC, December 2024
- Impacts of Summer Storms on the Thermal Regime of Dead Run (Co-author) – Maryland Water Monitoring Council Annual Conference, November 2024
- Visualizing Thermal Fluctuations of the Dead Run Stream Network – Poster, Baltimore Ecosystem Study Annual Meeting, October 2023
- Thermal Fluctuations in a Maryland Use Class IV Stream – Poster, Maryland Water Monitoring Council Annual Conference, November 2023

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
