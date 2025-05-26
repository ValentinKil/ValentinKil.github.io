---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

## Submitted 
{% assign reversed_posts = site.polycopies | reverse %}
{% for post in reversed_posts %}
  {%if post.path contains 'Submit' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}


## Internships
{% assign reversed_posts = site.polycopies | reverse %}
{% for post in reversed_posts %}
  {%if post.path contains 'Stages' %}
    {% include archive-single.html %}
  {%endif %}
{% endfor %}

