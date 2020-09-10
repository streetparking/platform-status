---
layout: page
title: Documentation
permalink: /documentation/
---

  {% for post in site.categories.documentation %} {% if post.url %}
  <dl class="margin-bottom-40">
    <dt>
      <h3>
        <a href="{{ post.url | baseurl}}"
          >{{ post.title }} |
          <span class="date">{{post.date | date: "%m/%d/%Y"}}</span></a
        >
      </h3>
    </dt>
    <dd>
      {{ post.excerpt }}
      <a class="read-more" href="{{ post.url | baseurl}}">Continue Reading...</a>
    </dd>
  </dl>
  {% endif %} {% endfor %}
