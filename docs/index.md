---
non_post: true
---

# Don't forget to put on your Tinfoil Suit

The world is changing fast! A lot of the change is great. I love being able to talk
to my friends and family 3,000 miles away whenever I want, face-to-face, in real time.
The economy has exponentially improved year over year for decades (for the most part).
We've all benefited.

And yet...

Change is hard, it always is. The goal of Tinfoil Suit is to give you an instinct
for navigating technology without being taken advantage of. These posts are meant
to leave you confident and excited about our new world, not anxious and afraid.

Change is good, as long as you change with it.

## All Posts

{% for post in site.posts %}

### [{{ post.title }}]({{site.baseurl}}{{ post.url }})
{{ post.excerpt }}

{% endfor %}
