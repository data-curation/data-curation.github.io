---
layout: default
---

# Test

test page


  {% for post in paginator.posts %}
      <article>
      <div><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></div>
      <p><a href="{{ site.baseurl }}{{ post.url }}"> &#9679; </a> {{ post.date | date_to_string }}</p>
      <div>
        {{ post.content }}
        </div>
             {% include tags.html %}
     </article>
     <hr>
  {% endfor %}


<ul>
  {% if paginator.previous_page %}
      <li><a href="{{ paginator.previous_page_path | prepend: site.baseurl | replace: '//', '/' }}">&larr; Newer</a></li>
  {% endif %}
    {% if paginator.next_page %}
      <li><a href="{{ paginator.next_page_path | prepend: site.baseurl | replace: '//', '/' }}">Older &rarr;</a></li>
  {% endif %}
</ul>
