---
layout: default
title: "226 Scouting"
---

<ul>
    These are the stories and adventures our scouts have gone on from their campouts and service projects
{% for post in site.posts %}
{% include post_snippet.html 
    title=post.title 
    url=post.url 
    pretty_date=post.pretty_date 
    excerpt=post.excerpt
    primary_image=post.primary_image
    primary_image_alt=post.primary_image_alt
%}
{% endfor %}

</ul>
