---
layout: default
title: Episodes
---
<div class = "episodes">

<h2> Episodes </h2>
<ul>
{% for post in site.posts %}    

    <li>
        <a href="{{ post.url }}"> {{ post.title }} </a>
    </li>
    
{% endfor %}
