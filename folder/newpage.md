---
layout: post
title: Blogging Like a Hacker
---
new page
<ul>
      {% for p in site.pages %}
        <li>
          <a href="{{ p.url }}">{{ p.title }}</a>
        </li>
      {% endfor %}
    </ul>

![My helpful screenshot]({{ "/home-icon.png" | absolute_url }})

