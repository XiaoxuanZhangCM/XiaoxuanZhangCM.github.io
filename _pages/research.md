---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---


My research centers on developing novel theories, methods, and tools to advance scientific computing. I am particularly interested in developing accurate, robust, and efficient multiphysics, multiscale, and data-driven computational models. I collaborate with experts from different fields to solve challenging science and engineering problems. Following are descriptions of my current projects and some snapshots of my past projects. 

<h3>Current projects </h3>
{% include archive-recent-research.html %} 

<h3>Past projects </h3>
<nbsp>

{% include base_path %}

{% for post in site.research%}
  {% include archive-single.html type="grid" %}
{% endfor %}

