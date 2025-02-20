---
type: PageLayout
title: This is a new page
sections:
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
        text: |
          **"Present the plan in a table format with columns for
          platform, content type, and key message. Include
          engagement hooks for each piece. Keep individual
          posts under 200 characters."**
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Tip for prompts
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Use Role Assignment
        subtitle: Tip
        text: |
          Prompt eg: 

          **"As a senior ML engineer specializing in neural networks
          Review this PyTorch implementatio
          Identify performance bottleneck
          Suggest optimization strategies for training speed"**
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
        title: Add Specific Constraints
        subtitle: Tip
        text: |
          Prompt eg: 

          **"Analyze our customer churn dataset with these
          parameters
          Focus on users inactive > 30 day
          Compare behavioral patterns pre-chur
          Include statistical significance test
          Output visualizations in seaborn**
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
        title: Request Examples and Variation
        subtitle: Tip
        text: |
          Prompt eg: 

          **"Provide 2 implementations of this sorting algorithm
          Optimized for memory efficienc
          Optimized for processing speed Include time
          complexity analysis for each**
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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: Google prompt framework
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Task Context Reference Evaluate Iterate
        subtitle: ''
        text: >
          Examples with this framework:  


          1.  **Write a social media post featuring this image. The post should
          be fun, short, and focus on the fact that it's a colelction of new
          designs I'm selling. (with reference attached)**


          2\. **I"m a gym manager and we have a new gym schedule. Write an email
          informing our staff of the new schedule. Highlight the fact that the
          M/W/F Cardio Blast class changed from 7:00am to 6:00am. Make the email
          professional and friendly. and short so that the readers can skim it
          quickly.**
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
        title: Iteration Methods
        subtitle: ''
        text: |+


          1.  **Revisit the prompting framework**

          2.  **Separate prompts into shorter sentences**

          3.  **Trying different phrasing or switching or an analog task**

          4.  **Introduce contraints**

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
  - type: FeaturedItemsSection
    title:
      type: TitleBlock
      text: AI hallucinations / Biases
      color: text-dark
      styles:
        self:
          textAlign: center
    subtitle: >-
      1) Evaluate Suitability: Ensure AI fits the task and doesn't reinforce
      harmful biases.2) Get Approval: Obtain company concent before using AI on
      projects.3) Protect Privacy: Use secure tools and avoid exposing sensitive
      data.4) Validate Outputs: Review all AI-generated content before
      sharing.5) Be Transparent: Disclose AI use to teams and clients.
    items: []
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
