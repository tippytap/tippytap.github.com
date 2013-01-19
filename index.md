---
layout: default
title: Code
tagline: I like it.
---
<!-- {% include JB/setup %} -->

### I want to learn more. 
I wanna post little experiments and things I figure out here. 


<section class="right">
  <h3>Recent posts</h3>
  <ul class="posts">
    {% for post in site.posts %}
      <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
  </ul>
</section>


