---
tags: false
layout: collection
title: CMS posts
description: A separate section to use a CMS in your design history.
pagination:
  data: collections.cms-posts
  reverse: true
  size: 50
permalink: "cms-posts/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---
