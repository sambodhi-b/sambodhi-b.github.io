---
layout: default.liquid
---
## Blog!
Testing out Cobalt Build on push to main repo using github actions

{% for post in collections.posts.pages %}
#### {{post.title}}

[{{ post.title }}]({{ post.permalink }})
{% endfor %}
