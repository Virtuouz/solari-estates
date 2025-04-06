---
_schema: default
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Private Idaho Mansion Open House
metaDesc:
customCode:
  headCode: ''
  bodyCode: ''
happeningImage: /assets/uploads/303940.jpg
imageAltText:
image: >-
  {% if happeningImage %}{{happeningImage}}{% else
  %}{{happenings.defaultImage}}{% endif %}
cancelled: false
happeningDate: 2026-04-06T17:00:00Z
tags:
summary:
permalink: >-
  {% assign title = title | slugify %}/happenings/{{ page.filePathStem |
  fileSubstringFilter | append: title | downcase }}{% if pagination.pageNumber >
  0 %}/page/{{ pagination.pageNumber }}{% endif %}/index.html
socialImage: '{{ image }}'
layout: layouts/page.html
id: f5a099cb-01e4-4b34-82df-257c77b548f6
hero:
content_blocks: []
_inputs:
  headCode:
    type: code
    comment: Add code at the end of the <head> tag
  bodyCode:
    type: code
    comment: Add code before the </body> tag
---
