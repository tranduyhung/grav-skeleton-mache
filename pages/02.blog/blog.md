---
title: Blog
blog_url: blog

sitemap:
    changefreq: monthly
    priority: 1.03

content:
    items: @self.children
    order:
        by: date
        dir: desc
    limit: 6
    pagination: true

feed:
    description: Sample Blog Description
    limit: 10

pagination: true
---

Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et
dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation
