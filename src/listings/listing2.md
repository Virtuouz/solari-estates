---
_schema: default
id: d7cee8c9-998f-4155-9580-30027293ae9f
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Listing2
metaDesc:
customCode:
  headCode: ''
  bodyCode: ''
pageLink:
tags:
  - For Sale
  - Featured
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
keyInformation: This gated mansion is tucked away in northern Idaho.
hero:
  _bookshop_name: sections/simpleHero
  sectionId:
  heading:
    _bookshop_name: generic/heading
    content:
      highlightEyebrow: false
      eyebrow: ''
      headline: Private Mansion in Idaho
      description: This gated mansion is tucked away in northern Idaho.
      buttons: []
      headingHierarchy: h2
    styles:
      contentAlignment: left
      textAlignment: left
      visualInterest: none
      visualInterestColor: '#000000'
      highContrast: false
      contrastColorGroup:
      contrastAgainst:
      textClassOverride:
content_blocks:
  - _bookshop_name: generic/tags
    styles:
      tagColors: greyscale
  - _bookshop_name: sections/imageCarousel
    content:
      showNote: true
      images:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/303940.jpg
          imageAlt:
          yAxisPosition:
          imageSizes:
          class:
          imageNumber:
    styles:
      color_group: primary
  - _bookshop_name: sections/informationCards
    content:
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Overview
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: left
          textAlignment: left
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup:
          contrastAgainst:
          textClassOverride:
      cards:
        - heading:
            _bookshop_name: generic/heading
            content:
              highlightEyebrow: false
              eyebrow: ''
              headline: Lorem ipsum
              description: >-
                Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
                faucibus ex sapien vitae pellentesque sem placerat. In id cursus
                mi pretium tellus duis convallis.
              buttons: []
              headingHierarchy: h2
            styles:
              contentAlignment: left
              textAlignment: left
              visualInterest: none
              visualInterestColor: '#000000'
              highContrast: false
              contrastColorGroup:
              contrastAgainst:
              textClassOverride:
        - heading:
            _bookshop_name: generic/heading
            content:
              highlightEyebrow: false
              eyebrow: ''
              headline: Lorem ipsum
              description: >-
                Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
                faucibus ex sapien vitae pellentesque sem placerat. In id cursus
                mi pretium tellus duis convallis.
              buttons: []
              headingHierarchy: h2
            styles:
              contentAlignment: left
              textAlignment: left
              visualInterest: none
              visualInterestColor: '#000000'
              highContrast: false
              contrastColorGroup:
              contrastAgainst:
              textClassOverride:
        - heading:
            _bookshop_name: generic/heading
            content:
              highlightEyebrow: false
              eyebrow: ''
              headline: Lorem ipsum
              description: >-
                Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
                faucibus ex sapien vitae pellentesque sem placerat. In id cursus
                mi pretium tellus duis convallis.
              buttons: []
              headingHierarchy: h2
            styles:
              contentAlignment: left
              textAlignment: left
              visualInterest: none
              visualInterestColor: '#000000'
              highContrast: false
              contrastColorGroup:
              contrastAgainst:
              textClassOverride:
    styles:
      color_group: primary
      card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
      cardBackground: true
  - _bookshop_name: sections/simpleTextBlock
    content:
      heading:
        _bookshop_name: generic/heading
        content:
          highlightEyebrow: false
          eyebrow: ''
          headline: Details
          description: ''
          buttons: []
          headingHierarchy: h2
        styles:
          contentAlignment: left
          textAlignment: left
          visualInterest: none
          visualInterestColor: '#000000'
          highContrast: false
          contrastColorGroup:
          contrastAgainst:
          textClassOverride:
      text:
        _bookshop_name: generic/textBlock
        text: >-
          Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
          faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi
          pretium tellus duis convallis. Tempus leo eu aenean sed diam urna
          tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas.
          Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut
          hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent
          per conubia nostra inceptos himenaeos.


          Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
          faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi
          pretium tellus duis convallis. Tempus leo eu aenean sed diam urna
          tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas.
          Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut
          hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent
          per conubia nostra inceptos himenaeos.


          Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
          faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi
          pretium tellus duis convallis. Tempus leo eu aenean sed diam urna
          tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas.
          Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut
          hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent
          per conubia nostra inceptos himenaeos.


          Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
          faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi
          pretium tellus duis convallis. Tempus leo eu aenean sed diam urna
          tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas.
          Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut
          hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent
          per conubia nostra inceptos himenaeos.


          Lorem ipsum dolor sit amet consectetur adipiscing elit. Quisque
          faucibus ex sapien vitae pellentesque sem placerat. In id cursus mi
          pretium tellus duis convallis. Tempus leo eu aenean sed diam urna
          tempor. Pulvinar vivamus fringilla lacus nec metus bibendum egestas.
          Iaculis massa nisl malesuada lacinia integer nunc posuere. Ut
          hendrerit semper vel class aptent taciti sociosqu. Ad litora torquent
          per conubia nostra inceptos himenaeos.
    styles:
      color_group: primary
  - _bookshop_name: sections/actionBar
    content:
      buttons:
        - _bookshop_name: generic/button
          url: '#'
          openInNewTab: false
          text: Call now
          color_group: primary
          colorFromGroup: primary
          ghostButton: false
          formSubmit: false
        - _bookshop_name: generic/modalButton
          id: 68c38138-bc3b-4cea-a78a-45f22e291f71
          resource:
            _bookshop_name: simple/formBuilder
            formName:
            sectionId:
            successPage:
            form_elements:
              - _bookshop_name: generic/form/textInput
                label: First Name
                placeholder: ''
                id: 1d8c6eb5-7630-4aaa-9657-60a0e3028c2c
                required: true
                helperText: ''
              - _bookshop_name: generic/form/textInput
                label: Last Name
                placeholder: ''
                id: e88e4549-703c-4e6c-9ed7-f407d7c83e1f
                required: true
                helperText: ''
              - _bookshop_name: generic/form/emailInput
                label: Email
                id: 201b57e3-6573-45ce-b98e-b1904bf12bba
                required: true
                placeholder:
                helperText: ''
              - _bookshop_name: generic/form/dateInput
                label: Tour Day
                id: cfa7f23f-399e-42ba-8afe-2d504248332b
                required: true
                minToday: true
                min:
                maxToday: false
                max:
                helperText: ''
              - _bookshop_name: generic/form/timeInput
                label: Tour Time
                placeholder: ''
                id: 1aee797e-0dfc-41e0-85cf-c9541cc6dd2c
                helperText: Pick a time between 10:00 and 17:00
                min: 10:00 am
                max: 5:00 pm
            submitButton:
              text: Submit
              color_group: primary
              colorFromGroup: primary
              ghostButton: false
              formSubmit: true
          form_color_group: primary
          text: Schedule a tour
          color_group: primary
          colorFromGroup: primary
          ghostButton: true
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
