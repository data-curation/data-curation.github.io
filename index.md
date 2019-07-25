---
layout: default
---

<h1 class="post-title">Canadian Data Curation Forum</h1>
---
<br />

The Canadian Association of Research Libraries’ Portage Network in collaboration with McMaster University Library will host a SSHRC-funded Canadian Data Curation Forum at McMaster University in Hamilton from <strong>October 16 to 18, 2019</strong>.  

The goal of the Forum is to establish a national Community of Practice that will catalyze the development/adoption of data curation1 standards, practices, tools, and skills within and across disciplines and institutions. It will bring together library data specialists, research data managers, and discipline and functional experts from a range of institutions and organizations. The Forum will integrate a variety of keynote talks, discussions, and workshops to with the objectives of a) facilitating communication and collaboration around data curation practices and standards, and b) developing skill and training resources.

<br /> 

The Forum will comprise the following events: 

* The Data Curation [Training Event](../agenda#data-curation-training-event) (Wednesday, 16-Oct to Thursday, 17-Oct) will consist of a series of interactive skill-building workshops intended to develop data curation skills in individuals who are responsible for and/or interested in data curation activities. A nominal registration fee will apply to the training event. 

* The Data Curation [Community-Building Forum](../agenda#-community-building-forum) (Thursday 17-Oct to Friday, 18-Oct) will feature a variety of plenary and discussion sessions intended to build a vision for a national approach to data curation in Canada. Attendees will be active participants in building a national data curation road map during and following the event. There is no registration fee associated with the community-building sessions.

<br />
**[Apply now](../register) to attend!**
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
