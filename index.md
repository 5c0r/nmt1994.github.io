---
layout: page
title: Welcome to Vi Elite's Blog
tagline:
---
{% include JB/setup %}

Hello friends who spent your precious time to visit this website !

<img width="100%" src="{{ site.url}}/assets/media/welcome.jpg" />



This page is still in under construction and I still have not get any idea on what to write / discuss here :(
Currently there are many topics that I would like to discuss , and they are on priority from top to bottom :

1. Back-end Development:
- .NET
- Java
- JavaScript ( Node )
- PHP ( Somehow this is not my expertise )
2. Front-end Development
- CSS Practices
3. Others IT-Related stuffs which I found interesting
- Virtualization
- Internet of Things ( IoT )
- Computer hardware, Software and stuffs
4. Which books are good to read if you are a person interests in:
- IT
- Life & Experience
- Biography
5. My own life experience when being a student/intern/worker


# My blogspots are here


<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
