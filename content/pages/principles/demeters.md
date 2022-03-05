---
title: Demeter's Law or the Principle of Least Knowledge
seo:
  title: Developer-Forge
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Demeter's Law or the Principle of Least Knowledge
      keyName: property
    - name: 'og:description'
      value: Demeter's Law or the Principle of Least Knowledge
      keyName: property
      relativeUrl: true
layout: page
---

Demeter's Law states an object should never know about the internal details of other objects. It's been designed to promote loose coupling in software architecture.

It's often [summarised](https://en.wikipedia.org/wiki/Law_of_Demeter#:~:text=The%20Law%20of%20Demeter%20(LoD,specific%20case%20of%20loose%20coupling.) like so:

*The below description uses the word unit- but this can essentially mean function/classs/module etc*

-  Each unit should only have limited knowledge about other units that are closely related to itself (*example* don't have different, random parts of the codebase coupled to one another)
- Each unit should only talk to it's "friends", not strangers
- Only talk to your immeadiate friends

Friends in this example just relates to how close the units are in similarity. If you have a class called `Engine` tightly coupled to `Food` - this is a big red flag, those two words semantically don't fit "together"

By following Demeter's Law you will ensure the code you create will be more maintainable and adaptable, as your code is "composed" of lots of independent units, that you can change, without changing huge parts of your code that other units rely on.