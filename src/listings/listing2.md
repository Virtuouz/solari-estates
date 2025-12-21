---
_schema: default
id: d7cee8c9-998f-4155-9580-30027293ae9f
draft: false
eleventyExcludeFromCollections: false
disableNav: false
disableSitemap: false
title: Listing2
metaDesc: null
customCode:
  headCode: ''
  bodyCode: ''
pageLink: null
tags:
  - For Sale
  - Featured
canExpire: false
expireDate: null
permalink: >-
  /listings/{% assign id = id | uuidHashFilter%}{% capture varPagePath %}{% if
  pageLink%}{% assign pageLink = pageLink | slugify%}{{  page.filePathStem
  |fileSubstringFilter | append: pageLink | append: "-" | append: id  }}{% else
  %}{{  page.filePathStem |fileSubstringFilter | append: id }}{% endif %}{%
  endcapture %}/{{varPagePath | strip}}/index.html
layout: layouts/listing.html
listingImage: /assets/uploads/303940.jpg
imageAltText: null
keyInformation: This gated mansion is tucked away in northern Idaho.
hero:
  _bookshop_name: sections/simpleHero
  sectionId: null
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
      contrastColorGroup: null
      contrastAgainst: null
      textClassOverride: null
    _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
  _componentId: simpleHero-8c1dcda7-535f-4605-9e3c-86685737f008
content_blocks:
  - _bookshop_name: generic/tags
    styles:
      tagColors: greyscale
    _componentId: tags-e18b3ebc-ef8f-4406-b127-c6278297bc6b
  - _bookshop_name: sections/imageCarousel
    content:
      showNote: true
      images:
        - _bookshop_name: generic/image
          imagePath: /assets/uploads/303940.jpg
          imageAlt: null
          yAxisPosition: null
          imageSizes: null
          class: null
          imageNumber: null
          _componentId: image-c1cbbc3b-f7dc-4577-8f8f-c37dd7943db2
          imageWidths: null
      sectionId: null
      heading: 'bookshop:structure:headingBlocks'
    styles:
      color_group: primary
    _componentId: imageCarousel-3c829311-df32-41c0-a254-9e0f1afccf29
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
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
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
              contrastColorGroup: null
              contrastAgainst: null
              textClassOverride: null
            _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
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
              contrastColorGroup: null
              contrastAgainst: null
              textClassOverride: null
            _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
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
              contrastColorGroup: null
              contrastAgainst: null
              textClassOverride: null
            _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
      sectionId: null
    styles:
      color_group: primary
      card_color_group: 5c9075f8-80f9-4482-b041-91cffdfe02be
      cardBackground: true
    _componentId: informationCards-8b479207-cb46-43d4-935c-54de4e1f3dd0
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
          contrastColorGroup: null
          contrastAgainst: null
          textClassOverride: null
        _componentId: heading-89db575d-4583-4ff0-89a6-d6931371a72a
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
        _componentId: textBlock-0b312f24-1509-4d49-991b-889f4d113886
      sectionId: null
    styles:
      color_group: primary
    _componentId: simpleTextBlock-1a5ab00c-5c73-435e-abf1-efdfaf30e675
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
          _componentId: button-5a055703-3064-4c18-af21-4c4ef537e497
        - _bookshop_name: generic/modalButton
          id: 68c38138-bc3b-4cea-a78a-45f22e291f71
          resource:
            _bookshop_name: simple/formBuilder
            formName: null
            sectionId: null
            successPage: null
            form_elements:
              - _bookshop_name: generic/form/textInput
                label: First Name
                placeholder: ''
                id: 1d8c6eb5-7630-4aaa-9657-60a0e3028c2c
                required: true
                helperText: ''
                _componentId: textInput-c93e5b13-0af4-4308-af72-64efb41b1579
              - _bookshop_name: generic/form/textInput
                label: Last Name
                placeholder: ''
                id: e88e4549-703c-4e6c-9ed7-f407d7c83e1f
                required: true
                helperText: ''
                _componentId: textInput-c93e5b13-0af4-4308-af72-64efb41b1579
              - _bookshop_name: generic/form/emailInput
                label: Email
                id: 201b57e3-6573-45ce-b98e-b1904bf12bba
                required: true
                placeholder: null
                helperText: ''
                _componentId: emailInput-c344a86b-60c9-4329-bd1c-f2a5106f53d8
              - _bookshop_name: generic/form/dateInput
                label: Tour Day
                id: cfa7f23f-399e-42ba-8afe-2d504248332b
                required: true
                minToday: true
                min: null
                maxToday: false
                max: null
                helperText: ''
                _componentId: dateInput-ac0d6300-996a-4b20-b5a8-9f5aa2a5da0b
              - _bookshop_name: generic/form/timeInput
                label: Tour Time
                placeholder: ''
                id: 1aee797e-0dfc-41e0-85cf-c9541cc6dd2c
                helperText: 'Pick a time between 10:00 and 17:00'
                min: '10:00 am'
                max: '5:00 pm'
                _componentId: timeInput-3d9b6e7a-2152-4724-834a-806bb4ef3308
            submitButton:
              text: Submit
              color_group: primary
              colorFromGroup: primary
              ghostButton: false
              formSubmit: true
            _componentId: formBuilder-1be2b859-3776-47b6-a974-0189cb33295e
            inboxKey: null
            subject: null
          form_color_group: primary
          text: Schedule a tour
          color_group: primary
          colorFromGroup: primary
          ghostButton: true
          _componentId: modalButton-ce57d451-a7dc-4222-9ef8-c7536c294970
    styles:
      color_group: primary
      colorFromGroup: background
    _componentId: actionBar-4c432c0e-c257-41cf-b1e6-ba42c804052e
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

