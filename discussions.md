---
layout: page
title: Discussions
---

<div id="home">
  <h2>Discussions</h2>
  <ul class="posts">
    {% for post in site.posts %}
      <li>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
            <span class="post-date">{{ post.date | date: "%m/%d/%Y" }}</span>
      </li>
    {% endfor %}
  </ul>
</div>
