---
type: PageLayout
title: Contact Us
sections:
  - type: GenericSection
    title:
      type: TitleBlock
      text: Generic Section With A Form
      color: text-dark
    subtitle: Section with a form subtitle
    text: |+
      **Contact Information**

      You may contact us using the details below:

      **Merchant Legal Entity Name:**
      CutCraft

      **Registered Address:**
      Siddharth Nagar, Dapodi, Pune,
      Pune, Maharashtra 411012

      **Operational Address:**
      Siddharth Nagar, Dapodi, Pune,
      Pune, Maharashtra 411012

      **Telephone:**
      9970571976

      **Email ID:**
      [cutcraftllp@gmail.com]()



    actions: []
    media:
      type: FormBlock
      fields:
        - type: TextFormControl
          name: name
          label: Name
          hideLabel: true
          placeholder: Your name
          isRequired: true
          width: full
        - type: EmailFormControl
          name: email
          label: Email
          hideLabel: true
          placeholder: Your email
          isRequired: true
          width: full
        - type: TextareaFormControl
          name: message
          label: Message
          hideLabel: true
          placeholder: Your message
          width: full
      submitButton:
        type: SubmitButtonFormControl
        label: Submit
        icon: arrowRight
        iconPosition: right
        style: primary
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
    badge:
      type: Badge
      label: Contact Us
      color: text-primary
    colors: bg-light-fg-dark
slug: contact-us
seo:
  type: Seo
  metaTitle: Pricing - Demo site
  metaDescription: This is the pricing page built with Netlify Create.
  socialImage: /images/main-hero.jpg
  metaTags: []
---
