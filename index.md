---
layout: blocks
title:
date: 2017-11-22T23:00:00.000+00:00
page_sections:
  # top navigation
  - template: navigation-header-w-button
    block: header-2
    logo: '/uploads/patrons/webLogo.png'
    navigation:
      - link: '/'
        link_text: Home
      - link: '#features'
        link_text: Features
      - link: '#contactus'
        link_text: Contact Us
      #- link: "#responsive"
      #  link_text: Responsive
      #- link: "#blocks"
      #  link_text: Blocks
    cta:
      #  url: https://app.forestry.io/quick-start?repo=forestryio/ubuild-jekyll&provider=github&engine=jekyll
      button_text: Coming Soon
  - template: hero-banner-w-image
    block: hero-2
    slug: kiosk_portrait
    headline: <strong>Patrons</strong><br>back to workplace
    content: Comprehensive visitor management software with a simple user experience and focus on reducing contact with any hardware on the building premises.
    cta:
      enabled: false
      url: https://github.com/forestryio/ubuild-jekyll
      button_text: 'See on GitHub '
    image:
      image: '/uploads/patrons/1-kiosk-portrait.png'
      alt_text: Visitor Mobile Portal
    #background_image: "/uploads/2018/06/21/hero-2-bg.png"
  - template: content-feature
    block: hero-3
    slug: features
    heading: <strong>Key Features</strong>
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: PreRegistration
    # slug: features
    headline: <strong>Pre-Registration<span class="light">&nbsp;</span></strong><span
      class="light">before reach the premises</span>
    content: Allow invitee to do self registration before arrive on the building to reduce the queue in registration area
    media:
      image: '/uploads/patrons/1-kiosk-portrait.png'
      alt_text: Visitor Mobile Portal
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: scanqr
    # slug: customize
    headline: <strong>Mobile-based Registration</strong><span class="light">&nbsp;by scan the QR Code</span>
    content: Provide mobile web based registration to allow system In current Covid-19 pandemic reducing contact on registration process will be the best
    media:
      image: '/uploads/patrons/scanme.png'
      alt_text: Mobile-Based Registrations
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: kiosk
    # slug: features
    headline: <strong>Self-service Registration<span class="light">&nbsp;</span></strong><span
      class="light">don&apos;t share your id card</span>
    content: Visitor can utilize Patrons Android based Self-service kiosk to do visitor registration
    media:
      image: '/uploads/patrons/kiosk.png'
      alt_text: kiosk
  - template: content-feature
    block: feature-1
    media_alignment: Right
    slug: biometric
    # slug: customize
    headline: <strong>Automatic Biometric Matching</strong><span class="light">&nbsp;to avoid queue</span>
    content: Verify ID Card Photo and captured photo during registration process
    media:
      image: '/uploads/patrons/biometric.png'
      alt_text: biometric
  - template: content-feature
    block: feature-1
    media_alignment: Left
    slug: office
    # slug: customize
    headline: <strong>Office 365 Integration</strong><span class="light">&nbsp;seamless booking</span>
    content: Booking the meeting room, and all attendee calendar in one action
    media:
      image: '/uploads/patrons/booking.png'
      alt_text: Office 365 Integration
  # - template: 1-column-text
  #   block: one-column-1
  #   slug: responsive
  #   headline: 16 Fully Responsive Design Blocks
  #   content: |
  #     The Design Blocks can be used without Forestry but to harness the power
  #     of Blocks we recommend using <a href="https://forestry.io">Forestry</a>. Once the site is imported you can immediately
  #     create new sites and make them fully customizable.
  # - template: full-width-media-element
  #   block: media-1
  #   image: "/uploads/2018/06/21/theme.png"
  #   caption: All Available Blocks
  #   slug: blocks
  - template: contact-us
    block: one-column-2
    slug: contactus
    headline: Contact Us
    content: <p><br><a href="mailto:info@thepatrons.co">info@thepatrons.co</a></p>
  - template: simple-footer
    block: footer-1
    content: Made with ❤︎<br>
      Copyright 2021 Patrons VMS
---
