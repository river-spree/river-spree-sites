---
layout: default
title: Posts | river-spree
---

<div class="row">

  <div id="tvtower-image" class="long-image four columns">
  </div>

  <div id="all-posts" class="eight columns"> 
    <h1>All Posts @ river-spree</h1>
    <ul class="posts">  
    {% for post in site.posts %}  
      <li>  
        <span>{{ post.date | date_to_string }}</span> &raquo;  
        <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a>  
      </li>  
    {% endfor %}  
    </ul>
  </div>

</div>

