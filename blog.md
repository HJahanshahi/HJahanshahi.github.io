---
layout: page
title: Blog
permalink: /blog/
---

<style>
  .blog-section {
    max-width: 800px;
    margin: 0 auto;
    padding: 20px;
    font-family: Arial, sans-serif;
  }
  .blog-section h2 {
    color: #007BFF;
    margin-bottom: 20px;
  }
  .blog-section p {
    margin-bottom: 20px;
    line-height: 1.6;
  }
</style>

<div class="blog-section">
  <h2>Blog</h2>
  <p>Welcome to my blog! Here, you'll find posts on various topics related to my research and interests. Feel free to explore and contact me if you have any questions or would like to discuss further.</p>
  <div>
    {% for post in site.posts %}
    <article>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <p>{{ post.excerpt }}</p>
    </article>
    <hr>
    {% endfor %}
  </div>
</div>
