---
layout: default
title: "226 Scouting"
---

<ul>
    These are the stories and adventures our scouts have gone on from their campouts and service projects
    {% for post in site.posts %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.excerpt }}</a>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
</ul>
