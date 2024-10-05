---
layout: default  # Change to the layout you want to use
title: "Home"    # Title of the page
description: "Welcome to my site!"  # Meta description for SEO
---

# Welcome to My Site

This is a brief introduction to my website. Here, you can find information about my projects, blog posts, and more!

## Latest Blog Posts

{% for post in site.posts %}
  * [{{ post.title }}]({{ site.baseurl }}{{ post.url }}) - {{ post.date | date: "%B %d, %Y" }}
{% endfor %}

## About Me

Hello! My name is [Pranay Yadav](https://pranay27sy.github.io/Stock-Market-Playbook/), and I'm passionate about exploring the dynamic world of stock markets. With a keen interest in finance and investing, I created this Stock Market Playbook to document my journey, strategies, and insights.

## Connect with Me

Feel free to reach out or follow me on social media:

- [Twitter](https://twitter.com/pranay27sy)
- [GitHub](https://github.com/Pranay27sy)
- [LinkedIn](https://linkedin.com/in/pranay27sy)

Thank you for visiting!
