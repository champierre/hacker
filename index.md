---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

{% assign posts = site.posts | sort: "date" %}
<ul>
{% for post in posts %}
  <li><h3><a href="/hacker{{ post.url }}">{{ post.title }}</a></h3></li>
{% endfor %}
</ul>
