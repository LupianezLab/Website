---
title: Publications
nav:
  order: 3
  tooltip: Selected works
---

# {% include icon.html icon="fa-solid fa-microscope" %}Publications

{% include section.html %}

## See our highlighted publications

{% capture col1 %}

{% include citation.html lookup="doi:10.1038/s41467-024-47658-x" style="rich" %} #miRNA

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1038/s41586-023-05868-1" style="rich" %} #skate

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}

{% include citation.html lookup="doi:10.1038/s41588-022-01117-9" style="rich" %} #anania

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1038/s41576-018-0007-0" style="rich" %} #structural variation

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}

{% include citation.html lookup="doi:10.1038/ng.3939" style="rich" %} #indian hedgehog

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1016/j.tig.2016.01.003" style="rich" %} #breaking tads

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

{% capture col1 %}

{% include citation.html lookup="doi:10.1016/j.cell.2015.04.004" style="rich" %} #disruptions

{% endcapture %}

{% capture col2 %}

{% include citation.html lookup="doi:10.1016/j.celrep.2015.01.016" style="rich" %} #engeneering

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{%
  include list.html
  data="citations"
  component="citation"
  style="rich"
%}
