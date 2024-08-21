---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Adrien Altieri
      color: text-dark
      type: TitleBlock
    subtitle: Directeur Magasin - Castorama Metz
    text: >
      Merci de l'intérêt que vous portez à l'amélioration de l'expérience client
      **Castorama**. En tant que directeur du magasin **Castorama Metz**, je
      suis à votre écoute pour vos retours, idées, avis, etc.
    actions:
      - label: Prendre rendez-vous
        altText: ''
        url: 'https://calendly.com/arnaud-derhan-castorama/30min'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
      - label: En savoir plus
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/adri.PNG
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
      styles:
        self:
          padding:
            - pt-0
            - pl-0
            - pb-0
            - pr-0
          margin:
            - mt-2
            - ml-2
            - mb-2
            - mr-2
          borderWidth: 8
          borderColor: border-light
          borderStyle: solid
    badge:
      label: Programmer un rendez-vous Téléphonique
      color: text-dark
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-8
          - pl-8
          - pb-8
          - pr-8
  - type: FeaturedItemsSection
    title:
      text: Faire un retour
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Choisissez la méthode de contact à votre convenance.
    items:
      - type: FeaturedItem
        title: Téléphone
        subtitle: Rappel téléphonique
        text: >
          Laissez votre numéro de téléphone, et je vous rappellerai lors du
          créneau de votre choix, à sélectionner sur la page de rendez-vous.
        actions: []
        elementId: null
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: small
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Lightning bolt symbol on red background
          elementId: ''
          url: /images/Capture d’écran 2024-08-18 à 13.09.00.png
          styles:
            self:
              borderRadius: x-large
      - title: Visio
        subtitle: Conférence Teams/Zoom
        text: >
          Sélectionnez "Visio" lors de la prise de rendez vous, et un lien de
          réunion avec Adrien Altieri sera automatiquement généré à la date et
          l'heure choisies.
        image:
          url: /images/Capture d’écran 2024-08-18 à 13.12.55.png
          altText: Featured icon two
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: small
            flexDirection: row
            textAlign: left
            justifyContent: center
        type: FeaturedItem
      - title: Message
        subtitle: Courrier éléctronique
        text: >
          Si vous souhaitez simplement faire parvenir un message écrit à Adrien
          Altieri, c'est également possible. Une réponse vous sera donnée
          rapidement.
        image:
          url: /images/Capture d’écran 2024-08-18 à 13.16.43.png
          altText: Featured icon three
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: small
            flexDirection: row
        type: FeaturedItem
    actions:
      - type: Button
        label: Prendre rendez-vous
        altText: ''
        url: 'https://calendly.com/arnaud-derhan-castorama/30min'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
      - type: Button
        label: Envoyer un message
        altText: ''
        url: /message
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
    badge:
      label: Prise de contact
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
        margin:
          - mb-0
      subtitle:
        textAlign: center
  - title:
      text: Formulaire de contact
      color: text-dark
      type: TitleBlock
    subtitle: Indisponible pour une conversation ?
    text: >
      Vous ne souhaitez pas programmer une conversation téléphonique ? Pas de
      soucis, Adrien reste à votre écoute. N'hésitez pas à laisser un message
      avec vos commentaires, retours, ou avis : 
    media:
      fields:
        - name: name
          label: Name
          hideLabel: true
          placeholder: Votre Nom
          isRequired: true
          width: full
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Votre e-mail
          isRequired: true
          width: full
          type: EmailFormControl
        - name: message
          label: Message
          hideLabel: true
          placeholder: Votre message
          width: full
          type: TextareaFormControl
          isRequired: true
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
        label: Envoyer
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Contactez nous
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
    elementId: message
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
