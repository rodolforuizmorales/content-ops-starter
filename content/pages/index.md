---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: 'Empowering communities through free, high-quality sofware'
      color: text-dark
      type: TitleBlock
    subtitle: about us
    text: >
      seeb development is an indie startup founded in the middle of the jungle
      in Merida, Yucatan, Mexico with a passion for using technology to make a
      difference in the lives of those who need it most. With over two decades
      of experience, we’ve dedicated ourselves to developing free, high-quality
      applications that cater to the needs of underprivileged communities in
      Latin America and beyond.
    actions: []
    media:
      url: /images/seeb_logo.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: SEEB DEVELOPMENT
      color: text-primary
      type: Badge
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
      text: free android apps
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: >-
      brief introduction to seeb development to show our commitment to creating
      impactful software solutions
    items:
      - type: FeaturedItem
        title: 'Viewflix Lite: Global TV'
        subtitle: free tv
        text: >
          Enjoy a wide range of global TV channels right at your fingertips.
          With live streaming options from various international broadcasters,
          you can stay updated with the latest news, sports, and entertainment
          from around the world.
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
          url: /images/viewflix.png
          styles:
            self:
              borderRadius: xx-small
              padding:
                - pt-0
              borderWidth: 0
      - title: Rdio - FM & AM Live Radio
        subtitle: free radio
        text: >
          Listen to your favorite FM and AM radio stations from anywhere in the
          world. Whether it’s music, talk shows, news, or sports broadcasts,
          Rdio has got you covered with a diverse selection of stations.
        image:
          url: /images/rdio.png
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
      - title: Paragraph News
        subtitle: free news
        text: >
          Stay informed with concise news summaries from reputable sources.
          Paragraph News + delivers the latest updates in a short and
          easy-to-read format, covering topics such as politics, technology,
          sports, and entertainment.
        image:
          url: /images/paragraph.png
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
    actions: []
    badge:
      label: SEEB
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
  - subtitle: tools
    images:
      - url: /images/empathy-logo.svg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/wellster-logo.svg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/vise-logo.svg
        altText: Vise logo
        type: ImageBlock
      - url: /images/telus-logo.svg
        altText: Telus logo
        type: ImageBlock
      - url: /images/contenful-logo.svg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
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
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
