---
title: Publications
nav:
  order: 2
  tooltip: Published works
---

# {% include icon.html icon="fa-regular fa-file" %}Publications

We do very cool work, check it out.

{% include section.html %}

## Highlighted

{%
  include list.html
  data="citations"
  component="citation"
  filters="group: featured"
  style="rich"
%}


{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{%
  include list.html
  data="citations"
  component="citation"
  style="rich"
  filters="title: .+" %
%}

