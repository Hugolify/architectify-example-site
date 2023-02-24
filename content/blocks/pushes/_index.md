---
isPage: true
draft: false
title: Push
description: Add some cards push with image and button in column.
image:
  src: /images/uploads/credit-card-2-front.svg
hero:
  title: Block pushes
  text: Add some cards push with image and button in column.
  cta:
    text: See examples
    url: "#main"
    blank: false
  cta_second:
    blank: true
    text: Documentation
    url: https://github.com/hugolify/hugolify-template/wiki/Block-pushes
blocks:
  - type: alert
    state: warning
    text: Be careful to always have sufficient contrast between the text and the image for it to be readable.
  - type: pushes
    column: 1
    background: false
    title: 1 column
    text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: "#"
          text: Lorem ipsum
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/darwin-vegher-mV4oTSZR4eA-unsplash.jpg
          alt: ""
  - type: pushes
    column: 1
    background: false
    title: 1 column, align center
    text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: "#"
          text: Lorem ipsum
        offset: center
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/volodymyr-kondriianenko-n2EXdta0MeM-unsplash.jpg
          alt: ""
  - type: pushes
    column: 1
    background: false
    title: 1 column, align end
    text: Nam eleifend nisl tellus, porta lacinia
    items:
      - cta:
          blank: false
          url: "#"
          text: Lorem ipsum
        offset: end
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
        image:
          src: /images/uploads/matic-kozinc-njYp4KqjqF8-unsplash.jpg
          alt: ""
  - type: pushes
    column: 2
    background: false
    title: 2 columns
    text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: "#"
          text: Lorem ipsum
        image:
          src: /images/uploads/matic-kozinc-njYp4KqjqF8-unsplash.jpg
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        image:
          src: /images/uploads/volodymyr-kondriianenko-n2EXdta0MeM-unsplash.jpg
          alt: ""
        offset: start
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
  - type: pushes
    column: 2
    background: false
    title: 2 columns without images and custom background color
    text: Curabitur in tortor et odio congue suscipit sit amet quis purus.
    items:
      - cta:
          blank: false
          url: "#"
          text: Lorem ipsum
        background_color: "#000"
        offset: start
        title: Lorem ipsum
        text: Nam eleifend nisl tellus, porta lacinia lectus sollicitudin non.
      - cta:
          blank: false
        offset: center
        background_color: "#0E0F60"
        title: Faucibus maximus nunc
        text: Phasellus tellus purus, pellentesque eu velit vel, faucibus maximus nunc.
---
