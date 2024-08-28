---
layout: archive
title: "Publications"
permalink: /publications_conference/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

23333
<div><h2> Journal </h2></div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.type == 'Journal' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

<div><h2> Conference and Talk </h2> </div>
<hr style="border-color:black;">
{% for post in site.publications reversed %}
  {% if post.type == 'Conference' %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}
