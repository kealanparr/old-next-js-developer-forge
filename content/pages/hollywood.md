---
title: Hollywood Principle
seo:
  title: Theme Style Guide
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Theme Style Guide
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
      value: Theme Style Guide
    - name: 'twitter:description'
      value: >-
        A reference for suggested typographic treatment and styles for your
        content
    - name: 'twitter:image'
      value: images/1.jpg
      relativeUrl: true
layout: page
---

The Hollywood Principle refers to the often repeated phrase in pop-culture "Don't call us, we'll call you"

There are a huge amount of applications to this rule as it's quite general, but the often cited example is:

In any framework/library there are certain function that you shouldn't call yourself.

In React for example, you don't need to ever call `componentDidMount()` as it will be called for you.

At the end of the constructor you don't need to work out how to call this function, it will be called for you, `componentDidMount` is saying "Don't call me, I will call you when I'm ready." 

This is true for so many other frameworks/libraries

- In Angular, you don't need to call `ngOnDestroy()` it will be called for you in the lifecyle
- In Vue, you don't need to call `beforeCreate()` it will be called for you in the lifecyle

By having these life-cycle methods that get called for you at pre-determined times, the schedule and flow of your app is simplified significantly.
