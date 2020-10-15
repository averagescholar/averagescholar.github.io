---
layout: page
title: Computer Vision
---

Introduction to Computer Vision ([link](https://www.udacity.com/course/introduction-to-computer-vision--ud810))
        
<ul>
{% assign no_post = true %}
{% for tag in site.tags %}
    {% if tag[0] == "vision udacity" %}
        {% if tag[1].size > 0 %}
            {% assign no_post = false %}
        {% endif %}

        {% for post in tag[1] %}
            <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
    {% endif %}
{% endfor %}
{% if no_post == true %}
    <li>No post yet</li>
{% endif %}
</ul>

