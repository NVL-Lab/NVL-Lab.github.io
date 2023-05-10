---
---

# Welcome to our lab!

We are in construction!.

{% include section.html %}

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

Interested in meeting the faces behind our research? Our team will be comprised of passionate researchers, scientists, engineers, and professionals from diverse backgrounds. Click through and say say hello to our team!

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

Explore our latest published papers and see the exciting discoveries and advancements we've made in our field. Our research is centered around two topics:  neuroprosthetic learning, which offers invaluable insights into the neural basis of learning, and novel optical approaches to neuroprosthetics. Embark on this exciting journey with us.

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

If you're interested in utilizing our code, we invite you to check out our latest releases and repositories. Our code is fully open source, and we welcome contributions from the community. Join us in advancing the field and making a meaningful impact through collaborative development.

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
