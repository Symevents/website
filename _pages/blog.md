---
title: Our Blog
description: Get the latest updates & news from the Linaro team, including
  industry news, our latest projects & company news. Click to read the latest
  updates.
permalink: /blog/
tags_enabled: true
jumbotron:
  class: text-center about_header
  title: Our Blog
  title-class: font-weight-bold my-5
  inner_class: py-5
  image: /assets/images/content/blog_sm.jpg
flow:
  - row: container_row
    sections:
      - format: custom_include
        source: blog/post_search.html
        payload:
          name: url
          search_label: LinaroBlog
          category: blog
      - format: custom_include
        source: blog/display_latest_posts.html
        category: blog
        limit: 22
---
