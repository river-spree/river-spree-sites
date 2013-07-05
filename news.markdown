---
layout: default
title: News | river-spree
---

<div class="row">
  <h1 class="sixteen columns">Recent Posts @ river-spree</h1>
</div>

{% for post in site.posts limit:5 %}  
<hr />
<div class="row">

  <div class="post-head twelve columns">	
    <h2>{{ post.title }}</h2>
    <p class="meta">{{ post.date | date_to_string }}</p>
  </div>

  <div class="post twelve columns">
  {{ post.content }}
  </div>

</div>
{% endfor %}  
