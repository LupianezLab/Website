---
title: Publications
nav:
  order: 3
  tooltip: Selected works
---

# {% include icon.html icon="fa-solid fa-wrench" %}Projects

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include tags.html tags="publication, resource, website" %}

{% include search-info.html %}

{% include section.html %}

## Higlighted

{% capture col1 %}

{% include citation.html lookup="doi:10.1101/2024.10.10.617585" style="rich" %}

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1242/dev.201562" style="rich" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}

{% include citation.html lookup="doi:10.1002/jez.b.23142" style="rich" %}

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1126/science.aaz2582" style="rich" %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## All

{% include list.html component="card" data="projects" filter="!group" style="small" %}
