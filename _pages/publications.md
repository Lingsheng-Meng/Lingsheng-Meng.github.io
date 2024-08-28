---
layout: archive
title: "Publications and Conferences"
permalink: /publications/
author_profile: true
---

{% include base_path %}


<div><h2> Journal </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.type == 'Journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


<div><h2> Conference and Talks </h2> </div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.type == 'Conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}


