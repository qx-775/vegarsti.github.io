---
layout: default
title: Vegard Stikbakke
---

# Vegard Stikbakke

I'm a software engineer from Norway.
I work at [Dune Analytics](https://duneanalytics.com/) and I studied statistics and computer science at the University of Oslo.

My email is <code>vegard.stikbakke@gmail.com</code>, don't hesitate to say hi!
My resume is [here](assets/pdf/Resume.pdf).

<table>
  <tr>
    <td><a href="https://github.com/vegarsti"><i class="fab fa-github" aria-hidden="true"></i></a></td>
    <td><a href="https://twitter.com/vegardstikbakke"><i class="fab fa-twitter" aria-hidden="true"></i></a></td>
    <td><a href="https://www.goodreads.com/user/show/3400170-vegard-stikbakke"><i class="fab fa-goodreads" aria-hidden="true"></i></a></td>
    <td><a href="https://linkedin.com/in/vegardstikbakke"><i class="fab fa-linkedin" aria-hidden="true"></i></a></td>
    <td><a href="assets/pdf/Resume.pdf"><i class="fas fa-file-alt" aria-hidden="true"></i></a></td>
  </tr>
</table>


## Posts

<div>
{% for post in site.posts %}
<div>
<a href="{{ post.url }}">{{ post.title }}</a>
<br />{{ post.date | date: "%B %-d, %Y" }}
</div>
<br />
{% endfor %}
</div>
