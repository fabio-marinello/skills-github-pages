---
title: Temporary name
---

This is the content on my homepage. Let's test the markdown:

1. Do lists work?
2. Does mathematics like $\int f(x) dx$ also work? What about \(a+b=c\)?

Thanks!

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> – {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>

