---
layout: default
title: "Personal Finance for College Students"
---

# Broke But Smart
## Personal Finance Advice That Actually Works for College Students

Welcome to Broke But Smart – where we turn financial stress into financial success, one smart decision at a time.

I'm just like you. I've been broke, I've made the mistakes, and I've learned the hard way how to build wealth starting with literally nothing. Now I'm sharing what actually works.

No trust funds. No wealthy parents. Just real strategies for real students.

## Latest Articles

{% for post in site.posts limit: 10 %}
<article>
    <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
    <div class="post-meta">{{ post.date | date: "%B %d, %Y" }}</div>
    <div class="post-excerpt">
        {% if post.excerpt %}
            {{ post.excerpt | strip_html | truncatewords: 30 }}
        {% else %}
            {{ post.content | strip_html | truncatewords: 30 }}
        {% endif %}
    </div>
    <a href="{{ post.url | relative_url }}" class="read-more">Read More →</a>
</article>
<hr>
{% endfor %}

---

## Why Trust Me?

I'm not here to sell you courses or promise overnight wealth. I'm here because I wish someone had told me this stuff when I was struggling to afford ramen.

[Learn more about my story →](/about/)

---

*Ready to stop being broke? Let's get smart about money together.*