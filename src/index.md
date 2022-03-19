---
title: "Healthy Lifestyle"
layout: base.njk
---

# Lets get some education about how our body functions, and know whether we are doing it right?

<ul>
{% for post in collections.posts %}
<li>
<a href="{{ post.url }}">
  {{ post.data.title }}
  <img src="/img/{{ post.data.title }}.jpg" alt="image">
  <br/>
</a>

</li>

{% endfor %}

</ul>
