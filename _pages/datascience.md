---
title: "Data Science Posts by Tags"
permalink: /datascience/
---
index of data science projects:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>