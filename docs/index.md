# Technical Literacy

This is a blog about technical literacy

## All Posts

<div>
  {% for post in site.posts %}
    <h3><a href="{{site.baseurl}}/{{ post.url }}">{{ post.title }}</a></h3>
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</div>
