---
layout: default
---

# Test

test page


<ul class="listing">
{% for post in site.posts %}
  {% capture y %}{{post.date | date:"%Y"}}{% endcapture %}
  <li class="listing-item">
    <time datetime="{{ post.date | date:"%Y-%m-%d" }}">&#9679;{{ post.date | date_to_string }}</time>
    <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>
