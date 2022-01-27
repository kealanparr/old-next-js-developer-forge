---
title: Components of a great software team
excerpt: Components of a great software team
date: '2022-01-26'
thumb_img_path: images/1.jpg
thumb_img_alt: Two developers plan out a User Interface on a whitebaord
content_img_path: images/1.jpg
content_img_alt: Components of a great software team
seo:
  title: Great software teams
  description: The first blog post on Developer-Forge
  extra:
    - name: 'og:type'
      value: article
      keyName: property
    - name: 'og:title'
      value: the first post
      keyName: property
    - name: 'og:description'
      value: >-
        Components of a great software team
      keyName: property
    - name: 'og:image'
      value: images/1.jpg
      keyName: property
      relativeUrl: true
layout: post
---

I've worked across a few different sectors, teams, tech-stacks *etc* and started to think about the patterns I think great teams follow.

### Linting
To ensure consistency, performance and clarity across a codebase - it's normally linted to some level.
Bonus points if the build system automatically fixes common linting errors.
### Fast, non-fragile pipelines
When you either merge your feature branch, or push into master - you have fast CI/CD pipelines that don't regularly break/hang.
### Automated testing
Normally as part of your pipeline, you have a host of unit and integration tests that run, and place a comment on the Merge Request is appropiate.
### Pre-push checks
For smaller non-test related checks, you may have pre-push checks that ensure your commit message follow a certain pattern/references a ticket *etc*
### Unit tests
Most of the significant helper functions/core part of your codebase has fast, useful unit tests - with edge cases considered - that're updated.
### Warnings flagged on problem files
If you have files that a lot of your codebase relies on, you can automatically email people (seniors?) based on these files being changed.
Just to ensure test scope is correct, or that the solution is in the right file for example.
### Easy to deploy
You can quickly and simply deploy to test on an environment.
### Easy to fiddle the code
You don't have to run 5 different repo's at once - with hard to set-up steps, to start debugging on live/uat/dev.
### Fast builds
Your build system takes less than 1 minute.
### Modular
You have correctly modularised, and seperated out your code.
Whether you use a microservice/microfrontend or similar - your code is clearly split and divided.
Sensible folder structure and file organisation.
### Sensible automations
This depends on the company, but manual repeated tasks are targeted with automations.
I've seen systems that automatically rollback code if logging (front-end or back-end) suddenly spikes on a code release.
I've seen releases get automated to save time.
I've seen kubernetes being used because developers kept getting called out at early hours to ssh onto boxes and restart them.
### Sensible logging
Logging can be an anti-pattern- but sensible logs in the front-end and back-end can also help you triage issues, and understand how many customers are facing errors.
Helps you to see if you're getting "better" or "worse".
### Address technical debt
The team is able to advocate for technical debt to be removed, rather than only ever writing new code.
### Regressions
There are regressions conducted on each release to ensure big items (log in *etc*) aren't broken - either manual or test-automations.
### Enough test environments
You don't have developers tripping over environments, and wiping one anothers code off the env.
Normally looks something like: devtest, uat, preprod and prod.
### Perf testing considered
Huge catch-all, but performance in the front-end and back-end is considered and measured.
### Useful 1:1's to help you grow
There are good and bad 1:1 meetings.
Good one's help you learn, grow as a developer and talk about your progression.
Bad one's aren't worth attending.
### A good way to unblock
If someone gets stuck, there is a recognised way to unblock.
Whether you just slack your Senior/Tech buddy or drop a message in a "help" channel - and someone can either pair with you, or rubber duck you to a solution.
### Good documentation
Documentation is considered, written and edited.
Documentation forms part of the description of "done".
### Version control
Version control is used effectively.
You are able to view old versions and new versions of code on production to understand when issues may have been introduced - like a manifest editor.
### Code re-use libraries
Code re-use is considered, and there are shared code libraries where necessary.
### Test harnesses, mocked scenarios
Mocking can be super fragile, so taken with a grain of salt here.
But scenarios can be mocked in a test harness or storybook - to view different permutations/edge cases.
### Good onboarding
This final step comes about when everything else is done well, but onboarding is considered and criticism taken on-board.
The codebases are painless to set up (containerised?) - and have as much automated as possible.
You're given a tech buddy to ask questions to if you get stuck.
