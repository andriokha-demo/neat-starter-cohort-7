---
title: This is a new blog post
description: This is the description field
author: Andy
date: 2021-06-09T18:59:41.656Z
tags:
  - Tags
---
This is the body field.: "Layout", name: "layout", widget: "hidden", default: "layouts/post.njk"} # - **can use blog template alias optionally if you set it up previously
      - {label: "Tags", name: "tags", widget: "hidden", default: "blog"}  # -**  - This is optional
      - {label: "Title", name: "title", widget: "string"}
      - {label: "Publish Date", name: "date", widget: "datetime"}
      - {label: "Featured Image", name: "thumbnail", widget: "image"}
      - {label: "Rating (