---
_schema: default
draft: false
title: Home
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
removeFromNavigation: false
eleventyNavigation:
  key: Home
  order: 1
  title: null
  parent: null
  url: null
pageLink: /
permalink: >-
  {% if pageLink == 'blog' or pageLink == 'Blog' %}/{{pageLink | slugify}}{% if
  pagination.pageNumber > 0 %}/page/{{ pagination.pageNumber }}{% endif
  %}/index.html{% elsif pageLink %}/{% assign pagelink = pageLink | slugify
  %}{{  page.filePathStem | fileSubstringFilter | append: pagelink | downcase
  }}/index.html{% else %}/{% assign title = title | slugify %}{{
  page.filePathStem | fileSubstringFilter | append: title | downcase
  }}/index.html{%endif %}
metaDesc: null
customCode:
  headCode: ''
  bodyCode: ''
layout: layouts/page.html
hero:
  _bookshop_name: sections/fullImageTextBottomHero
  content:
    sectionId: null
    highlightEybrow: false
    eyebrow: Where Prestige Meets Home
    headline: Solari Estates
    description: >-
      Experience the pinnacle of elegance and sophistication with Solari
      Estates.
    buttons:
      - _bookshop_name: generic/button
        url: null
        openInNewTab: false
        text: Explore homes
        color_group: primary
        colorFromGroup: primary
        ghostButton: false
        formSubmit: false
        _componentId: button-5a055703-3064-4c18-af21-4c4ef537e497
      - _bookshop_name: generic/button
        url: '#'
        openInNewTab: false
        text: About us
        color_group: primary
        colorFromGroup: text
        ghostButton: true
        formSubmit: false
        _componentId: button-5a055703-3064-4c18-af21-4c4ef537e497
    image:
      _bookshop_name: generic/image
      imagePath: /assets/uploads/mansion.jpg
      imageAlt: null
      yAxisPosition: null
      imageSizes: null
      class: null
      imageNumber: null
      imageWidths: null
      _componentId: image-c1cbbc3b-f7dc-4577-8f8f-c37dd7943db2
  styles:
    color_group: primary
    backgroundOpacity: 50
  _componentId: fullImageTextBottomHero-b0e632cd-24ba-4fdf-b15b-e20780e23c4d
content_blocks:
  - _bookshop_name: sections/listingsAll
    content:
      sectionId: null
      showNote: true
      filterCollection: null
      listingCount: 50
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Exclusive Properties
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: left
          textAlignment: left
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
      tags: null
      showExpired: false
      showAvailable: true
      showDisqualified: false
      showGeneral: true
      noListingsHeading: null
    styles:
      color_group: primary
      card_color_group: primary
      colorFromGroup: background
      listingCardStyle: horizontal
    _componentId: listingsAll-f427e5b0-8adb-4d27-951b-7263d0ecfc27
  - _bookshop_name: sections/upcomingHappening
    contents:
      sectionId: null
      showNote: true
      showCancelled: true
      tags: null
      showCountdown: true
      noHappeningsHeading: null
    styles:
      color_group: primary
      countDownPosition: center
      backgroundOpacity: 50
    _componentId: upcomingHappening-fecfa290-d5e0-49c4-ac0d-3fc71564856b
  - _bookshop_name: sections/servicesSection
    content:
      sectionId: null
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Our Premium Services
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: left
          textAlignment: left
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
      showNote: true
    styles:
      color_group: primary
      cardStyle: cleanCard
    _componentId: servicesSection-d06c51f7-7385-4443-8423-400d3f52e2e9
  - _bookshop_name: sections/sideBySideStandard
    content:
      sectionId: null
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: About us
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: left
          textAlignment: left
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
      entries:
        - _bookshop_name: generic/leftRight
          content:
            heading:
              _bookshop_name: generic/heading
              content:
                highlightEyebrow: false
                eyebrow: ''
                headline: About Solari Estates
                description: >-
                  Lorem ipsum dolor sit amet consectetur adipiscing elit.
                  Quisque faucibus ex sapien vitae pellentesque sem placerat. In
                  id cursus mi pretium tellus duis convallis. Tempus leo eu
                  aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus
                  nec metus bibendum egestas. Iaculis massa nisl malesuada
                  lacinia integer nunc posuere. Ut hendrerit semper vel class
                  aptent taciti sociosqu. Ad litora torquent per conubia nostra
                  inceptos himenaeos.


                  Lorem ipsum dolor sit amet consectetur adipiscing elit.
                  Quisque faucibus ex sapien vitae pellentesque sem placerat. In
                  id cursus mi pretium tellus duis convallis. Tempus leo eu
                  aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus
                  nec metus bibendum egestas. Iaculis massa nisl malesuada
                  lacinia integer nunc posuere. Ut hendrerit semper vel class
                  aptent taciti sociosqu. Ad litora torquent per conubia nostra
                  inceptos himenaeos.


                  Lorem ipsum dolor sit amet consectetur adipiscing elit.
                  Quisque faucibus ex sapien vitae pellentesque sem placerat. In
                  id cursus mi pretium tellus duis convallis. Tempus leo eu
                  aenean sed diam urna tempor. Pulvinar vivamus fringilla lacus
                  nec metus bibendum egestas. Iaculis massa nisl malesuada
                  lacinia integer nunc posuere. Ut hendrerit semper vel class
                  aptent taciti sociosqu. Ad litora torquent per conubia nostra
                  inceptos himenaeos.
                buttons: []
                headingHierarchy: h2
              styles:
                contentAlignment: left
                textAlignment: left
                visualInterest: none
                visualInterestColor: '#000000'
                highContrast: false
                contrastColorGroup: null
                contrastAgainst: null
                textClassOverride: null
              _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
            image:
              _bookshop_name: generic/image
              imagePath: /assets/uploads/home/about-us.jpg
              imageAlt: null
              yAxisPosition: null
              imageSizes: null
              class: null
              imageNumber: null
              imageWidths: null
              _componentId: image-c1cbbc3b-f7dc-4577-8f8f-c37dd7943db2
            entryNumber: 0
          styles:
            color_group: primary
            colorFromGroup: background
          _componentId: leftRight-eeb30bac-09e7-41ba-a9ab-424fd98ea4b8
    styles:
      color_group: primary
      startImageRight: false
      fullWidth: true
    _componentId: sideBySideStandard-f655a3f4-fd11-402d-9794-215be5328ad6
  - _bookshop_name: sections/textBreakReview
    content:
      sectionId: null
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: What Our Clients Say
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: center
          textAlignment: center
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
      usePersonImage: true
      reviews:
        - review: cf5af1f3-4b28-4280-a664-0ef482ae9215
        - review: e8b58d19-77b3-4e15-9d00-88808b9dc2b4
    styles:
      color_group: primary
    _componentId: textBreakReview-9ec5a449-69e1-49ed-aa59-0349a4cde163
  - _bookshop_name: sections/simpleCta
    content:
      sectionId: null
      CallToAction:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Ready to Experience <br>Luxury Living?
          description: ''
          buttons:
            - _bookshop_name: generic/button
              url: '#'
              openInNewTab: false
              text: Get in touch
              color_group: primary
              colorFromGroup: primary
              ghostButton: false
              formSubmit: false
              _componentId: button-5a055703-3064-4c18-af21-4c4ef537e497
            - _bookshop_name: generic/button
              url: '#'
              openInNewTab: false
              text: Browse homes
              color_group: primary
              colorFromGroup: primary
              ghostButton: true
              formSubmit: false
              _componentId: button-5a055703-3064-4c18-af21-4c4ef537e497
          headingHierarchy: h2
        styles:
          contentAlignment: center
          textAlignment: center
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
    styles:
      color_group: primary
    _componentId: simpleCta-55aa4315-260d-4b9f-a7e6-f4c494799681
_inputs:
  eleventyNavigation:
    hidden: removeFromNavigation
  headCode:
    type: code
    comment: Add code at the end of the <head> tag
  bodyCode:
    type: code
    comment: Add code before the </body> tag
---

