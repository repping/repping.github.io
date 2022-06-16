---
layout: archive
classes: wide
permalink: /blog/
title: "Blog"
---
Hear, hear, Apples logo is now a pear!


#### posts
____
{% for post in site.posts %}
<a href="{{ post.url }}">{{ post.title }}</a><br>
{{ post.excerpt }}<br><br>
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

