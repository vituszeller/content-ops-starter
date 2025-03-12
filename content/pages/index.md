---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Bitcoin Strategie & Projektumsetzung
      color: text-dark
      type: TitleBlock
    subtitle: Strategie. Beratung. Bitcoin. Dein Erfolg beginnt hier.
    text: >+
      **Von der Vision zur Realität:** Strategie, Beratung und Umsetzung für
      Bitcoin-Projekte und Tech-Startups.

    actions: []
    media:
      url: >-
        /images/A tree with golden Bitcoin coins as leaves symbolizes financial
        growth, with its roots glowing in turquois.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - type: FeaturedItemsSection
    title:
      text: Kernproduktangebot
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    items:
      - type: FeaturedItem
        title: Bitcoin Strategie
        subtitle: ∞/21M
        text: >
          Auch Euer Unternehmen kann von Bitcoin und dessen Potenzial
          profitieren. Wir finden die passende Strategie und helfen bei der
          Umsetzung.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/Bitcoin_Strategie.png
          styles:
            self:
              borderRadius: x-large
        tagline: ''
      - title: Beratung & Projektumsetzung
        subtitle: Von der Beratung zur Realität
        text: >+
          **Idee. Planung. Umsetzung.** Wir transformieren deine Vision in ein
          erfolgreiches Tech- oder Bitcoin-Projekt – mit klarer Strategie und
          praxisnaher Umsetzung.

        image:
          url: /images/icon3.svg
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
        type: FeaturedItem
      - title: Startup Strategie
        subtitle: zero to one
        text: >+
          Wir begleiten dein Tech- oder Bitcoin-Startup auf dem Weg von der
          Vision zur Realität – mit klarem Plan und nachhaltigem Wachstum.

        image:
          url: /images/icon2.svg
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
    actions: []
    badge:
      label: 'Von der Vision zur Realität: Strategie, Beratung und Umsetzung'
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
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
      text: Schnelleres und nachhaltiges Geschäftswachstum
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: ''
    text: >+
      Bitcoin revolutioniert die Finanzwelt – wir helfen dir, diese Chance
      strategisch zu nutzen und dein Geschäft nachhaltig zu skalieren.

      Nutze das Potenzial von Bitcoin, um dein Business zukunftssicher und
      wachstumsstark aufzustellen.

      Profitiere von unserer Expertise und setze Bitcoin gezielt für
      langfristigen Unternehmenserfolg ein.

    badge:
      label: Bitcoin ist die Zukunft – wir zeigen dir den Weg.
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    colors: bg-light-fg-dark
    styles:
      self:
        flexDirection: col
        justifyContent: center
      subtitle:
        textAlign: center
    type: GenericSection
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
      text: Kontaktformular für Anfragen.
      color: text-dark
      type: TitleBlock
    subtitle: ''
    text: >
      Nehmen Sie entweder via Email unter vitus.zeller \[@] gmail.com oder über
      das Formular Kontakt mit mir auf. Für telefonische Anfragen, rufen Sie
      bitte unter +49 1578 1824735 an.
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
      label: Kontakt
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
