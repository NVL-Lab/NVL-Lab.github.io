---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

We are a young group starting to grow.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/banner_lab.png" dark=true %}
## Join Our Growing, Young Team!
{% include section.html%}

We're on the lookout for talented individuals at all levels, from postdocs to undergraduates. If you're interested, we want to hear from you. Let us know:

- **Motivation.** Why you want to join our lab and how your vision aligns with ours.
- **Questions.** The specific questions you're passionate about addressing.
- **Project.** If you have a project in mind, we'd love to hear about it!
- **Background.** Help us understand how your unique expertise can help us achieve our goals.

We're excited to build a collaborative and inclusive environment. Get in [touch](https://nvl-lab.github.io/contact/)  to start the conversation!

### A bit of advice when applying to any lab:
The aforementioned points are essential considerations when applying to any lab. When reaching out to a PI, aim to address these questions concisely in 2-3 paragraphs. If you have read any of the lab's papers, share your thoughts on them and how you envision building upon their findings. This approach demonstrates genuine interest in the lab rather than submitting a generic application. And let's be honest, we scientist are a proud bunch. We love to hear how cool our research is! However, authenticity is crucial. If you find yourself forcing a fit with a lab, then that lab may not be the best choice for you. Research is a challenging and sometimes unrewarding journey; don't make it more difficult by selecting a lab that doesn't align with your scientific aspirations.

Remember, this advice applies to any application you submit. Best of luck in your endeavors!

{% include section.html background="images/banner_lab.png" dark=true %}

## The lab picture by picture!

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
