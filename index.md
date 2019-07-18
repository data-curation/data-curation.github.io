---
layout: default
---

<h1 class="post-title">Canadian Data Curation Forum</h1>
## October 16-18, 2019, Hamilton ON



<h1 class="post-title">News</h1>

<ul class="listing">
{% for post in site.posts %}
  <li class="listing-item">
   <p><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }} | {{ post.date | date: "%B %-d, %Y" }}</a></p>
    <div>
        {{ post.excerpt }}<a class="excerpt" href="{{ site.baseurl }}{{ post.url }}"> Keep reading...</a>
    </div>
  </li>

{% endfor %}
</ul>
