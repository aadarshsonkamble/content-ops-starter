---
type: PageLayout
title: This is a new page
sections:
  - type: CarouselSection
    items:
      - type: FeaturedItem
        title: Business Consulting
        tagline: Feature 2
        subtitle: Be in good company
        text: >-
          Sed ut perspiciatis unde omnis iste natus error sit voluptatem
          accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae.
          explicabo.
        image:
          type: ImageBlock
          url: /images/img-placeholder.svg
          altText: Business consulting
          elementId: ''
          styles:
            self:
              borderRadius: medium
        actions: []
        colors: bg-dark-fg-light
        styles:
          self:
            padding:
              - pt-9
              - pb-9
              - pl-9
              - pr-9
            textAlign: left
            borderRadius: large
            flexDirection: row
            justifyContent: center
    variant: tabs-nav
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Framework Breakdown
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Set the Stage (Context)
        subtitle: |-
          Framework 
          Breakdown
        text: |+
          *   Tell the AI who it's talking to

          *   Define the expertise level needed

          *   Specify any constraints or limitations

              eg, **"You're a data scientist analyzing our quarterly sales
              data. Identify key revenue patterns, create
              visualizations, and highlight anomalies. Focus on
              customer segments and regional variations."**

        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Define the Task (Action)
        subtitle: |-
          Framework 
          Breakdown
        text: |
          →
          **"You're a senior Python instructor. Create a step-by
          step learning plan for data structures, including
          Practice exercises for lists and dictionarie
          Real-world examples using panda
          Common pitfalls to avoid"**
        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            textAlign: left
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
      - type: FeaturedItem
        title: Specify the Output (Format)
        subtitle: |-
          Framework 
          Breakdown
        text: |2+

           "Present the plan in a table format with columns for 
          platform, content type, and key message. Include 
          engagement hooks for each piece. Keep individual 
          posts under 200 characters."

        actions: []
        colors: bg-neutral-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions: []
    variant: toggle-list
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pb-40
          - pt-16
          - pl-3
          - pr-3
        justifyContent: center
      subtitle:
        textAlign: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-3
          - pl-3
          - pb-3
          - pr-3
slug: help
isDraft: false
seo:
  type: Seo
  metaTitle: Landing Page
  metaDescription: Write here your new page's description including most relevant keywords.
  addTitleSuffix: true
  socialImage: /images/main-hero.jpg
  metaTags: []
---
