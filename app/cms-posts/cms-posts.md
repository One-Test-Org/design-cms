---
layout: collection
title: CMS  posts
description: A collection of posts to guide you how to build a design history by using the Netlify CMS.
pagination:
  data: collections.cms-posts
  reverse: true
  size: 50
permalink: "cms-posts/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
override:tags:
  - post
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
    order: 1
---
