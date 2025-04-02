---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located at the Andalusian Center for Developmental Biology (CABD), within the Department of Gene Regulation and Morphogenesis. CABD has been recognized for research excellence with the María de Maeztu distinction (2017–2021, 2022–2026) and is located on the campus of Universidad Pablo de Olavide (UPO), surrounded by a dynamic scientific community of university faculties and research centers. Our group is affiliated to the Spanish National Research Council (CSIC). You can find us on the first floor of CABD, in Lab 110!
{%
  include button.html
  type="email"
  text="dario.lupianez@csic.es"
  link="dario.lupianez@csic.es"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/ttV6ftSKTy1uRBqx9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/catedral.jpg"
  caption="Seville"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/cabd2.jpg"
  caption="Andalusian Center for Developmental Biology (CABD)"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}
