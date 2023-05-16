---
isPage: true
draft: false
title: Instagram
description: Add instagram feed
image:
  src: /images/uploads/instagram.svg
hero:
  title: Block Instagram
  text: Add instagram feed
  cta:
    blank: false
    text: See examples
    url: "#main"
blocks:
  - type: alert
    text: You need a valid access_token
    status: danger
  - type: instagram
    background: false
    heading:
      title: Instagram feed
    limit: 4
    token: ""
    cta:
      blank: true
      text: Discover on instagram
      url: https://www.instagram.com/sebouorhum
  - type: instagram
    background: true
    heading:
      title: Instagram feed
    limit: 6
    token: ""
---