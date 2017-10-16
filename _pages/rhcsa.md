---
layout: default
title:  "RHCSA"
date:   2017-09-26 22:54:31 -0500
permlink: "/RHCSA/"
---
<div class="home">

  <h1>RHCSA</h1>
  <h2>Chapters</h2>

  <ul class="posts">

{% for chapter in site.rhcsa %}
        {% if chapter.status == "publish" %}
      <li>
      <a class="post-link" href="{{ chapter.url}}">{{ chapter.title }}</a>
      </li>
       {% endif %}
{% endfor %}
  </ul>
</div>
