---
_schema: default
id: ab728581-3ae2-4929-9a08-22cc3d6761d4
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Private Estate in Idaho
metaDesc:
customCode:
  headCode: ''
  bodyCode: ''
pageLink:
tags:
canExpire: false
expireDate:
permalink: >-
  /listings/{% assign id = id | uuidHashFilter%}{% capture varPagePath %}{% if
  pageLink%}{% assign pageLink = pageLink | slugify%}{{  page.filePathStem
  |fileSubstringFilter | append: pageLink | append: "-" | append: id  }}{% else
  %}{{  page.filePathStem |fileSubstringFilter | append: id }}{% endif %}{%
  endcapture %}/{{varPagePath | strip}}/index.html
layout: layouts/listing.html
listingImage: /assets/uploads/303940.jpg
imageAltText:
keyInformation: Available through
hero:
content_blocks:
  - _bookshop_name: generic/tags
    styles:
      tagColors: colorful
  - _bookshop_name: sections/imageCarousel
    content:
      showNote: true
      images: []
    styles:
      color_group: primary
  - _bookshop_name: sections/informationCards
    content:
      cards: []
    styles:
      color_group: primary
      card_color_group: primary
      cardBackground: true
  - _bookshop_name: sections/simpleTextBlock
    content: {}
    styles:
      color_group: primary
  - _bookshop_name: sections/actionBar
    content:
      buttons: []
    styles:
      color_group: primary
      colorFromGroup: background
_inputs:
  headCode:
    type: code
    comment: Add code at the end of the <head> tag
  bodyCode:
    type: code
    comment: Add code before the </body> tag
  tags:
    type: multiselect
    options:
      values: data.listingTags
  expireDate:
    hidden: '!canExpire'
    comment: The date the listing will expire. Time must be entered in UTC time.
    type: datetime
  keyInformation:
    label: Key information
    comment: >-
      Short description of the listing. Will be shown on the listing cards.
      Should be a few sentences long
    type: markdown
    options:
      link: true
      blockquote: false
      bold: true
      italic: true
      strike: true
      subscript: true
      superscript: true
      underline: true
      bulletedlist: true
      numberedlist: true
      indent: false
      outdent: false
      code: false
      embed: false
      horizontalrule: false
      image: false
      table: false
      undo: true
      redo: true
      removeformat: true
      copyformatting: true
---
