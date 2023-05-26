---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

## Join Our Growing, Young Team!

We're on the lookout for talented individuals at all levels, from postdocs to undergraduates. If you're interested, we want to hear from you. Let us know:

- **Motivation.** Why you want to join our lab and how your vision aligns with ours.
- **Questions.** The specific questions you're passionate about addressing.
- **Project.** If you have a project in mind, we'd love to hear about it!
- **Background.** Help us understand how your unique expertise can help us achieve our goals.

We're excited to build a collaborative and inclusive environment. Get in touch to start the conversation!

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/banner_lab.png" dark=true %}

the lab picture by picture!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
