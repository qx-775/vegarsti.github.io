---
layout: default
title: Vegard Stikbakke | Vegard Stikbakke
---

# Vegard Stikbakke

Some text about how I study statistics at [University of Oslo](http://google.com) and work with data science at [Kolonial.no](http://kolonial.no).

- [GitHub](https://github.com/vegarsti)
- [LinkedIn](https://no.linkedin.com/in/vegardstikbakke)
- [Twitter](https://twitter.com/vegardstikbakke)
- [Curriculum Vitae (resume?)](https://google.com) (pdf)

## Blog

[All posts](/blog.html)
{% for post in site.posts limit: 3 %}
- `{{ post.date | date: "%Y-%m-%d" }}` [{{ post.title }}]({{ post.url }}) {% endfor %}

## Projects

- Lorem ipsum
- [csvprint](http://github.com/vegarsti/csvprint)