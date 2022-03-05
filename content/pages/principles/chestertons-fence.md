---
title: Chesterton's Fence
seo:
  title: Developer-Forge
  description: A reference for suggested typographic treatment and styles for your content
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Chesterton's Fence
      keyName: property
    - name: 'og:description'
      value: Chesterton's Fence
      keyName: property
      relativeUrl: true
layout: page
---

The normal flow of another developer QA'ing your code is that they read the code, raise any issues they see with you or explain why they think the way you've fixed an issue, is the wrong way.

Sometimes when asking questions, they may ask you something you're not sure about.

*But why did we need that class before you deleted it in your merge request?*

"Oh.. I don't know why that class was added in the first place. I tested my work though and we definitely don't need it. It isn't doing anything, and the code works now"

Is that a good enough response? The developer said they've tested their code, and it does now work.

Chesterton's Fence is the perfect application to this situation.

Unless we can understand why something was initially the way it was, we can actually make things worse! Not better!

Maybe that class is only used during certain parts of the year (yes it does nothing now, but when it comes to Christmas and we have the hero banner image on the hompage it now won't work because you deleted the class that appends it!) Or maybe yes it isn't doing anything right now, but it's an important class that in the future (when another codebase release their code next week) will be hugely beneficial to stop your codebase error'ing as the new team has changed the data contract you both have.

If we don't understand *why* something was done, we can't make accurate, data based decision on what to do next.

So if the developer can't answer exactly why the class was first added and the problem it solves, Chestertons Fence teaches us to ask the developer to probe deeper, and not be so hasty in making their changes *even if it does work*.

*NB. I hope I have explained this well enough for you to understand, but the name Chesteron's Fence often has a similar [parable/quote](https://www.goodreads.com/quotes/833466-in-the-matter-of-reforming-things-as-distinct-from-deforming) accompanying it everytime it's explained, so let me also ensure you know it.*

> There exists in such a case a certain institution or law; let us say, for the sake of simplicity, a fence or gate erected across a road.  
The more modern type of reformer goes gaily up to it and says, "I don't see the use of this; let us clear it away." To which the more intelligent type of reformer will do well to answer: "If you don't see the use of it, I certainly won't let you clear it away. Go away and think. Then, when you can come back and tell me that you do see the use of it, I may allow you to destroy it."  
This paradox rests on the most elementary common sense. The gate or fence did not grow there. It was not set up by somnambulists who built it in their sleep. It is highly improbable that it was put there by escaped lunatics who were for some reason loose in the street. Some person had some reason for thinking it would be a good thing for somebody. And until we know what the reason was, we really cannot judge whether the reason was reasonable. It is extremely probable that we have overlooked some whole aspect of the question, if something set up by human beings like ourselves seems to be entirely meaningless and mysterious. <cite>G.K. Chesterton</cite>