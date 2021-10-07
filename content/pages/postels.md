---
title: Postel's Law or The Robustness Principle 
seo:
  title: Developer-Forge
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Postel's Law or The Robustness Principle
      keyName: property
    - name: 'og:description'
      value: Postel's Law or The Robustness Principle
      keyName: property
      relativeUrl: true
layout: page
---

Postel's Law or The Robustness Principle, is [simply defined](https://en.wikipedia.org/wiki/Robustness_principle) as "be conservative in what you send, be liberal in what you accept"

The application is, whenever machines need to talk to one-another, that they should accept messages that might not be perfectly formatted but the intention/message is clear, but should be very rigid in what they send.

If you send a message, you should ensure you conform completely to the specification/standards that governs your message format (JSON for example) but be flexible when receiving messages and ensure you don't crash/error if the input is malformed to you.