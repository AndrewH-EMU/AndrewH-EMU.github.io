---
layout: default
---

<img src="/profile.png" alt="Andrew Higgins" width="180" style="border-radius:30px;"/>

### About Me
I am a backend engineer specializing in systems architecture and optimization. I love programming scalable, creative solutions to complex problems. My technical background spans API integration, web development, game development, neural networks, and simulation tools. 

I am currently pursuing a BS in Computer Science at Eastern Michigan University, with an expected graduation in Fall 2026. 

[Connect with me on LinkedIn](https://www.linkedin.com/in/andrew-mr-higgins/)

---

### Weekly Developer Notes

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> - {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>
