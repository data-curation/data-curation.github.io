---
layout: default
---

This is some text

---------

<ul class="listing">
{% for post in site.posts %}
 
  <li class="listing-item">
   <p class="meta"><a href="{{ site.baseurl }}{{ post.url }}"></a> {{ post.date | date_to_string }}</p>
    <div>
        {{ post.content }}
    </div>
  </li>
  
  --------
{% endfor %}
</ul>
