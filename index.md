---
layout: default
---

<h1 class="post-title">Canadian Data Curation Forum</h1>
<br />

The Canadian Association of Research Libraries’ Portage Network in collaboration with McMaster University Library hosted the SSHRC-funded Canadian Data Curation Forum at McMaster University in Hamilton from <strong>October 16 to 18, 2019</strong>.  

The goal of the Forum was to establish a national Community of Practice that will catalyze the development/adoption of data curation standards, practices, tools, and skills within and across disciplines and institutions. It brought together library data specialists, research data managers, and discipline and functional experts from a range of institutions and organizations. The Forum integrated a variety of keynote talks, discussions, and workshops to with the objectives of a) facilitating communication and collaboration around data curation practices and standards, and b) developing skill and training resources.
<br /> 

Thank you to all of those who participated in and helped to facilitate the event. 

<br />
**The final event report with recommendations for a national approach to data curation services in Canada is now available in [English](https://zenodo.org/record/3894935) and [French](https://zenodo.org/record/3895031).**

<br />
**Event materials can be found [here](../materials).**

<br />
<br />

---
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
