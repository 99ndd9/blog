---
layout: default
title: コンテンツのアーカイブ
---

## 世界アーカイブへようこそ。

<!--<center><img style="border-radius:8px;" width="100%" src="../assets/img/banner5.jpg" alt="Banner"></center>-->
<!--![Header](https://capsule-render.vercel.app/api?type=Waving&color=timeGradient&height=300&animation=fadeIn&section=header&text=Archive&fontSize=100)-->

これはこの世界専用のアーカイブ集だ。お前には理解できん。

<ul>
  {% for post in site.blog %}
    <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<br />
<br />
<div align="left">
<a class="left" href="/blog/">← Previous</a>
</div>

<a onclick="topFunction()" id="btn-to-top">Top</a> 
