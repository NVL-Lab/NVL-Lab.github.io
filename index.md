---
---

# Welcome to our lab!
## Highlights
{% capture text %}

Discover what our lab is all about! Our research is aimed at uncovering the neural mechanisms of learning and developing innovative neuroprosthetic designs, paving the way for more effective treatment options.

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

Interested in meeting the faces behind our research? We are scientists, engineers, and professionals from diverse backgrounds. Click through and say say hello to our team!

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

{% capture text %}

Check out our latest papers to see what we've been working on. We’re exploring how neuroprosthetics can help us understand the mechanisms underlying learning and developing new algorithms for bidirectional brain-machine interfaces. 

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


If you’d like to use our code, feel free to explore our latest releases and repositories. Everything is open source, and we’re always excited to see contributions from the community. 

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
