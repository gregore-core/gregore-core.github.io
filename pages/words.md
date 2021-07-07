---
layout: page
title: words
permalink: /words/
---
{% for post in site.categories.words %}
  <div class="featured-posts" {% if post.image %}style="background-image:url({{ site.github.url }}/assets/img/{{ post.image }})"{% endif %}>
    <h2><a href="{{ site.github.url }}{{ post.url }}">
      <span>{{ post.title }}</span>
    </a></h2>
  </div>
{% endfor %}

<!-- {% if post.image %}style="background-image:url({{ site.github.url }}/assets/img/{{ post.image }})"{% endif %} -->