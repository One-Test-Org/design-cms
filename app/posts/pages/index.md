---
tags: false
layout: collection
title: CMS pages
description: A collection of pages created using the Netlify CMS
pagination:
  data: collections.posts.pages
  reverse: true
  size: 50
permalink: "pages/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
  eleventyNavigation:
    key: "{{ title }}"
    excerpt: "{{ description }}"
    parent: home
---
