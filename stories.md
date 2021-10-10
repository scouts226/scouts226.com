---
layout: main
---

{% for post in site.posts %}
{% include post_snippet.html
    title=post.title
    url=post.url
    post_date=post.date
    content=post.content
    primary_image=post.primary_image
    primary_image_alt=post.primary_image_alt
%}
{% endfor %}
