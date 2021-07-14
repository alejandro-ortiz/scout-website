---
layout: default
title: "226 Scouting"
---

![Scout meeting](https://cbc-scouts-226.s3.amazonaws.com/main_meeting.jpg){:class="photo"} <br>
Scouts BSA program which is for Middle School and High School youth consists of two units – one for boys and another for girls. These groups prepare today’s young people to make good choices by focusing on character and leadership development, citizenship training, and personal fitness. We are looking forward to a fun year of Scouting! With Troop 226 boys, girls, or pack 226

> Proverbs 2:26 Train up a child in the way they should go and when they are old they will not depart from it.




<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      {{ post.excerpt | stip_html }}
    </li>
  {% endfor %}
</ul>
