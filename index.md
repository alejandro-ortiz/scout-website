---
layout: default
title: "226 Scouting"
---

![Scout meeting](https://cbc-scouts-226.s3.amazonaws.com/main_meeting.jpg){:class="photo"} <br>
Scouting <br>
You may recognize scouts for "being prepared" or outdoorsy, but there is much more to it than that... The mission of scouting is to preparing youth for life! To prepare scouts to make good choices, the scouting program focuses on character development, leadership development, citizenship training, and personal fitness. Cub Scouts is for boys and girls in Kindergarten to 5th grade. Scouts BSA is for middle school and high school, and consists of two troops, one for boys and another for girls. During the school year, we meet Monday nights at 7:00.


<ul>
    {% for post in site.posts limit:3 %}
      <li>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.excerpt }}</a>
        <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
</ul>
