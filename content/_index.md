---
description: An example site for hugo-theme-gallery.
title: Hugo Gallery
resources:
  - src: corps.jpg
    params:
      cover: true # cover of the home page is used for OpenGraph cards, etc.
menus:
  main:
    name: Home
    weight: -1
# sub-galleries on list pages are sorted by date and weight (descending)
#cascade:
#  build:
#    publishResources: false # do not include full images. Also disable download
---
