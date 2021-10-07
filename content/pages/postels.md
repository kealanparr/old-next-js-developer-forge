---
title: Postel's Law or The Robustness Principle 
seo:
  title: Theme Style Guide
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Postel's Law or The Robustness Principle
      keyName: property
    - name: 'og:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Postel's Law or The Robustness Principle
    - name: 'twitter:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: page
---

Postel's Law or The Robustness Principle, is [simply defined](https://en.wikipedia.org/wiki/Robustness_principle) as "be conservative in what you send, be liberal in what you accept"

The application is, whenever machines need to talk to one-another, that they should accept messages that might not be perfectly formatted but the intention/message is clear, but should be very rigid in what they send.

If you send a message, you should ensure you conform completely to the specification/standards that governs your message format (JSON for example) but be flexible when receiving messages and ensure you don't crash/error if the input is malformed to you.