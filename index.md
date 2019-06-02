---
layout: default
---

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
   <p class="meta"><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} | {{ post.date | date: "%B %-d, %Y" }}</a></p>
    <div>
        {{ post.content }}
    </div>
  </li>

{% endfor %}
</ul>
