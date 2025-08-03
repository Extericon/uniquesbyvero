---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Welcome to Uniques by Vero!
      color: text-dark
      type: TitleBlock
    subtitle: 'One of a kind, wind chimes, authentic, hand made art'
    text: >
      Tired of all that empty space on your wall? Fill it in with some of my
      ***unique*** artwork!
    actions: []
    media:
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      url: /images/butterfly.jpg
    badge:
      label: ''
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-6
          - pl-6
          - pb-6
          - pr-6
        justifyContent: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Items on sale
      color: text-dark
      styles:
        self:
          textAlign: left
    items:
      - type: FeaturedItem
        title: Astral Sands
        subtitle: $ 88 – $ 176
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Faux Fur Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-0
              - pl-0
              - pb-0
              - pr-0
            textAlign: left
            borderRadius: none
            flexDirection: col
            justifyContent: center
      - type: FeaturedItem
        title: Tequila Sunrise
        subtitle: $ 44.99 – $ 90
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Cotton Knit Throws
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
      - type: FeaturedItem
        title: Caramel Dream
        subtitle: $117
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Chunky Cotton Knit Throw
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-light-fg-dark
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-8
          - pr-8
        justifyContent: flex-start
      subtitle:
        textAlign: center
  - type: GenericSection
    title:
      text: Works in Progress
      color: text-dark
      styles:
        self:
          textAlign: left
      type: TitleBlock
    subtitle: How it's made.
    text: ''
    actions: []
    elementId: null
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: row
        justifyContent: center
      subtitle:
        textAlign: left
    media:
      type: VideoBlock
      title: Title of the video
      url: /images/WIP.mp4
      autoplay: true
      loop: true
      muted: true
      controls: false
      aspectRatio: '16:9'
      styles:
        self:
          padding:
            - pt-2
            - pb-2
            - pl-2
            - pr-2
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: Need a custom piece?
      color: text-dark
      type: TitleBlock
    subtitle: Let me know what you have in mind.
    text: |
      We can work something out if my style suits your vision.
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
          type: TextareaFormControl
      elementId: contact-form
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contact Us
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
type: PageLayout
---
