---
_schema: default
id: e557e5aa-0372-491c-be1b-69bac0e4589c
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Listing1
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
          id: 3d8bd1f7-55c8-4f4f-a282-f25cd9c69d20
          resource:
            _bookshop_name: simple/formBuilder
            formName:
            sectionId:
            successPage:
            form_elements:
              - _bookshop_name: generic/form/textInput
                label: First Name
                placeholder: ''
                id: 98f69193-7dde-44a0-a84b-a7b0e8e7c70b
                required: true
                helperText: ''
              - _bookshop_name: generic/form/textInput
                label: Last Name
                placeholder: ''
                id: 59fcdfc9-f036-4959-8c93-b3f5f0f2acfd
                required: true
                helperText: ''
              - _bookshop_name: generic/form/emailInput
                label: Email
                id: bdf5e2a5-f0a0-408a-bcff-349d21829928
                required: true
                placeholder:
                helperText: ''
              - _bookshop_name: generic/form/dateInput
                label: Tour Day
                id: a557404a-4aaa-417f-9513-4f4c0582692a
                required: true
                minToday: true
                min:
                maxToday: false
                max:
                helperText: ''
              - _bookshop_name: generic/form/timeInput
                label: Tour Time
                placeholder: ''
                id: 97e2bf30-19b7-43d5-a9c7-9b5dd45e2fc7
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
