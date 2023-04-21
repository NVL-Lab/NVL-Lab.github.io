---
---

# NVL-Lab's Website

We are in construction!.

{% include section.html %}

## Highlights

{% capture text %}

Come check our research.

{%
  include button.html
  link="research"
  text="Cool projects inside"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/bmi_bwg_2_small.png"
  link="research"
  title="Our Research"
  text=text
%}

{% capture text %}

Come check our code.

{%
  include button.html
  link="code"
  text="Browse our code"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/code_2vsai.png"
  link="code"
  title="Our Code"
  flip=true
  style="bare"
  text=text
%}

{% capture text %}

Come check our papers.

{%
  include button.html
  link="publications"
  text="Papers and more papers"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/papers_small.png"
  link="publications"
  title="Our Papers"
  text=text
%}


{% capture text %}

Meet the team

{%
  include button.html
  link="team"
  text="Meet our team"
  icon="fa-solid fa-arrow-right"
  flip=true
  style="bare"
%}

{% endcapture %}

{%
  include feature.html
  image="images/lab_members_bgw_small_crop.png"
  link="team"
  title="Our Team"
  flip=true
  style="bare"
  text=text
%}
