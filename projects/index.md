---
title: Projects
nav:
  order: 2
  tooltip: Projects, PhD, MSc and BSc
---

# {% include icon.html icon="fa-solid fa-vials" %}Projects

Here you can explore our currently funded research projects and available topics for PhD, Master's, and Bachelor's theses. We aim to involve researchers at all career stages in ongoing research and place particular emphasis on scientific rigor, reliable data, and meaningful contributions to the projects they join.

{% include tags.html tags="project, PhD, MSc, BSc" %}

{% include search-info.html %}

{% include section.html %}

## Featured

{% include list.html component="card" data="projects" filter="group == 'featured'" %}

{% include section.html %}

## More

{% include list.html component="card" data="projects" filter="!group" style="small" %}
