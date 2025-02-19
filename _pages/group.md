---
layout: archive
title: "Our Group"
permalink: /group/
author_profile: true
---

{% include base_path %}

<!-- ![Members of our group visit the W. M. Keck Observatory](../images/trainor-group-700.jpg) -->

![Members of our group attend a talk in 2022 with my first astronomy project advisor](../images/trainor-ghez-group-750.jpg)


Meet some of the members of our galaxy formation research group here at F&M! Click the student names or images for more information on their projects.

{% for post in site.group %}
  {% include archive-single.html %}
{% endfor %}

***

## Former Group Members

Below are some of our former group members who are now doing other cool things in or out of astronomy! This section of the site is still under construction, so come back again to see more profiles and project descriptions.


{% for post in site.formergroup %}
  {% include archive-single.html %}
{% endfor %}
