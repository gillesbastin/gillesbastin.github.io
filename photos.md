---
title: "Photos"
categories: gallery_index
tags: photos
permalink: /photos/
layout: post
galleries:
  - title: Japon
    image: /photos/japan/20230927_0058.jpg
    url: /photos_japon
  - title: Link to image gallery
    image: /uploads/album/2.jpg
    url: /without-plugin/image-gallery
---

{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}
