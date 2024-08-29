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
  text="nvl2 at uab dot edu"
  link="nvl2@uab.edu"
%}
{%
  include button.html
  type="address"
  tooltip="Our lab"
  link="https://www.google.com/maps/place/UAB+Shelby+Interdisciplinary+Biomedical+Research/@33.5037983,-86.8013411,18.75z/data=!3m1!5s0x88891bea06f92875:0xd5054f6c90561814!4m14!1m7!3m6!1s0x88891bc18af02695:0xb37ae18adf6939da!2sShelby+Building!8m2!3d33.503782!4d-86.800573!16s%2Fg%2F11b6z1sx9_!3m5!1s0x88891bc22080c495:0x31bdf42c0843116b!8m2!3d33.5036657!4d-86.8005837!16s%2Fg%2F11c1qlfv_g?entry=ttu&g_ep=EgoyMDI0MDgyNy4wIKXMDSoASAFQAw%3D%3D"
%}

{% include section.html %}

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

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}

{% capture col1 %}

{% endcapture %}

{% capture col2 %}
We came, we saw, we kicked it's ass!
{% endcapture %}

{% capture col3 %}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 col3=col3 %}

