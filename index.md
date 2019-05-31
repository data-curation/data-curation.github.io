---
layout: default
---

This is some text

<ul class="listing">
{% for post in site.posts %}
 
  <li class="listing-item">
   <p class="meta"><a class="permalink" href="{{ site.baseurl }}{{ post.url }}"> &#9679; </a> {{ post.date | date_to_string }}</p>
    <div>
        {{ post.content }}
        </div>
             {% include tags.html %}
  </li>
{% endfor %}
</ul>
