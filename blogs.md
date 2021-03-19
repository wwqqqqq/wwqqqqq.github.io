---
layout: default
title: Blog
---

# [<span style="color:gray">Projects</span>](./index)   &nbsp;&nbsp; [<span style="color:gray">Résumé</span>](./resume) &nbsp;&nbsp; Blogs

<ul>
  {% for post in site.posts %}
    <li>
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


<br>
 <a href="#top"><i class="fa fa-angle-double-up fa-lg"></i> Back to top</a>