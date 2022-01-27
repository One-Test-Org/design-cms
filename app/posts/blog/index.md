---
tags: false
layout: collection
title: Blog Posts
description: A collection of posts created using Markdown and VScode
pagination:
  data: collections.blog
  reverse: true
  size: 50
permalink: "blog/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---
