---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg2.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - type: DividerSection
    title: Divider
    elementId: Video
    styles:
      self:
        width: narrow
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-4
        borderWidth: 1
  - type: CtaSection
    title: Portfolio
    text: |
      Carl-Wilhelm Brown
    actions:
      - type: Button
        label: Programming
        altText: ''
        url: /Programming
        showIcon: true
        icon: ''
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: Art
        altText: ''
        url: /Art
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
    colors: colors-f
    backgroundSize: inset
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-28
          - pl-4
          - pr-4
        flexDirection: col
        textAlign: center
---
