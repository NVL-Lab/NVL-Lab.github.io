---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

If you want to tell us how awesome we are.

{%
  include button.html
  type="email"
  text="nuria.vendrell.llopis at gmail"
  link="nuria.vendrell.llopis@gmail.com"
%}
{%
  include button.html
  type="phone"
  text="(---) 000-000"
  link="+1-555-867-5309"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps"
%}

{% include section.html %}

{% include cols.html col1=col1 col2=col2 %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Still no location"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Still no location"
%}

{% endcapture %}

{% include section.html dark=true %}

{% capture%}
We came, we saw, we kicked it's ass!
{% endcapture %}
