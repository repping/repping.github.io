---
layout: archive
classes: wide
permalink: /blog/
title: "Blog"
sidebar:
  - title: "Blog"
    image: /assets/images/500x300.png
    image_alt: "image"
    text: "Some text here."
author_profile: true
header:
  overlay_image: /assets/images/header_landingpage.png
---

{% for post in site.posts %}
___
{% if post.header.teaser %}
  <div class="thumbnail-container" class="align-left">
    <img src="{{ post.header.teaser | relative_url }}" alt="">
  </div>
{% endif %}
<!-- {% if include.type == "list" and teaser %}
  <div class="thumbnail-container">
    <img src="{{ teaser | relative_url }}" alt="">
  </div>
{% endif %} -->
<h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{{ post.excerpt }}

<br>
{% endfor %}



<!-- # List of all posts -->
<!-- <ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul> -->

<!-- # List of posts with a specific TAG -->
<!-- {% for tag in site.tags %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {{ post.excerpt }}
    {% endfor %}
  </ul>
{% endfor %} -->

<!-- # List of posts with a specific CATEGORY -->
<!-- {% for category in site.categories %}
  <h3>{{ tag[0] }}</h3>
  <ul>
    {% for post in tag[1] %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {{ post.excerpt }}
    {% endfor %}
  </ul>
{% endfor %} -->


<!-- More info: https://jekyllrb.com/docs/posts/ -->

