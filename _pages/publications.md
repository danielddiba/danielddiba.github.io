---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<sup>*</sup> The publications are listed in reverse chronological order. The links below each publication direct to the publisher's webpage or to a download of a free pdf.
You can also access a downloadable list of my publications in pdf [here](/files/publications/DanielDdiba_Publications_September2021.pdf).

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

