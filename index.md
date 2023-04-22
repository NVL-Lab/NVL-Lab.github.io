---
---

# Welcome to our lab!

We are in construction!.

{% include section.html %}

## Highlights

{% capture text %}

Discover what our lab is all about! We specialize in the field of neuroprosthetics, delving into the complexities of learning. Through our research, we aim to create innovative neuroprosthetic designs that will pave the way for more effective treatment options.

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

{% capture text %}

Explore our latest published papers and see firsthand the exciting discoveries and advancements we've made in our field. Our research is centered around the intricate topic of neuroprosthetic learning, offering invaluable insights into the neural basis of learning and revolutionary approaches to neuroprosthetics that push the boundaries of what's possible. Embark on this exciting journey of discovery with us and stay up-to-date on the latest developments in our field.

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

Interested in meeting the faces behind our research? Our team is comprised of passionate researchers, scientists, engineers, and professionals from diverse backgrounds. Click through and say say hello to our team!

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
