---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

<style>
  .blog-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
    gap: 1.5rem;
    margin-top: 1.5rem;
  }
  .blog-card {
    background: #ffffff;
    border: 1px solid #e1e4e8;
    border-radius: 6px;
    padding: 1.5rem;
    transition: transform 0.2s ease, box-shadow 0.2s ease;
    display: flex;
    flex-direction: column;
  }
  .blog-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 15px rgba(0,0,0,0.08);
  }
  .post-meta {
    font-size: 0.85em;
    color: #6a737d;
    margin-bottom: 0.75rem;
    font-family: monospace;
  }
  .post-title {
    margin: 0 0 1rem 0;
    font-size: 1.25rem;
    font-weight: 600;
    line-height: 1.3;
  }
  .post-title a {
    text-decoration: none;
    color: #24292e;
  }
  .post-title a:hover {
    color: #0366d6;
  }
  .post-excerpt {
    font-size: 0.95em;
    color: #586069;
    flex-grow: 1;
    line-height: 1.5;
    margin-bottom: 1.5rem;
  }
  .read-more {
    font-size: 0.9em;
    font-weight: 600;
    color: #0366d6;
    text-decoration: none;
    margin-top: auto;
  }
  .read-more:hover {
    text-decoration: underline;
  }
</style>

<div class="home">
  <div class="blog-grid">
    {% for post in site.posts %}
      <article class="blog-card">
        <div class="post-meta">
          <time datetime="{{ post.date | date_to_xmlschema }}">
            {{ post.date | date: "%B %-d, %Y" }}
          </time>
        </div>
        
        <h2 class="post-title">
          <a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        
        <div class="post-excerpt">
          {{ post.excerpt | strip_html | truncatewords: 30 }}
        </div>
        
        <a class="read-more" href="{{ post.url | prepend: site.baseurl }}">Read article →</a>
      </article>
    {% endfor %}
  </div>
</div>