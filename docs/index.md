# Technical Literacy

This is a blog about technical literacy

## All Posts

<div>
  {% for post in site.posts %}
    <a href="{{ post.url }}">{{ post.title }}</a>
    <br />
    <p>{{ post.excerpt }}</p>
  {% endfor %}
</div>
