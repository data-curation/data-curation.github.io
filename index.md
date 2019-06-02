---
layout: default
---

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
   <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} | {{ post.date | date: "%B %-d, %Y" }}</a></p>
    <div>
        {{ post.excerpt }}<a class="exerpt" href="{{ site.baseurl }}{{ post.url }}">Keep reading...</a>
    </div>
  </li>

{% endfor %}
</ul>
