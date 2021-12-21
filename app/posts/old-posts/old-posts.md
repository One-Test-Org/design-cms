---
tags: false
layout: collection
title: Old posts
description: A separate section to use in your design history.
pagination:
  data: collections.old-posts
  reverse: true
  size: 50
permalink: "old-posts/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---
