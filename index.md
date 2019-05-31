---
layout: default
---

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
   <p class="meta"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.date | date_to_string }}</a></p>
    <div>
        {{ post.content }}
    </div>
  </li>
<hr />
{% endfor %}
</ul>
