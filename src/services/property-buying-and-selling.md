---
_schema: default
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Property buying and selling
metaDesc:
customCode:
  headCode: ''
  bodyCode: ''
serviceImage: /assets/uploads/property-buying.jpg
imageAltText:
category:
summary:
pageLink:
permalink: >-
  /services/{% capture varPagePath %}{% if pageLink%}{% assign pageLink =
  pageLink | slugify%}{{  page.filePathStem |fileSubstringFilter | append:
  pageLink }}{% else %}{% assign title = title | slugify%}{{  page.filePathStem
  |fileSubstringFilter | append: title }}{% endif %}{% endcapture
  %}/{{varPagePath | strip}}/index.html
layout: layouts/page.html
id: 9ae11123-3e2e-495a-87eb-7b200ad39c6a
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
