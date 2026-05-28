---
title: Airbnb Front End Interview Questions
sidebar_label: Airbnb interview questions
description: Airbnb frontend interview questions covering JavaScript coding, UI development, system design, and LeetCode problems with real candidate experiences.
---

:::info Latest version on GreatFrontEnd

Find the latest version of this page on [GreatFrontEnd's Airbnb Front End Interview Guide](https://www.greatfrontend.com/interviews/company/airbnb/questions-guides?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook).

:::

## JavaScript coding questions

- Write a simple promise.
- Implement a `StoreData` class that adds key/value pairs and listens to value changes for keys. A Backbone Model-style key/value object with listeners. Recent Discord variants add: a global `change` listener that fires when any change is made, and `unset` should keep the listeners (soft-delete) so they re-fire when the attribute is set again. [Source](https://leetcode.com/discuss/post/348436/airbnb-phone-screen-implement-storedata-p3ypb/)
  - [Practice question](https://www.greatfrontend.com/questions/javascript/backbone-model?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)

## User interface coding questions

- Given an input and an endpoint which returns a JSON list, as a result, extend it to autocomplete on change, handle key navigation through the results.
  - [Read answer](https://www.greatfrontend.com/questions/system-design/autocomplete?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Given a star widget embedded in a form write the code to select the stars and submit the correct value through a normal form action. Make reusable for multiple star widgets.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/star-rating?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Implement a Tabs component.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/tabs?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Build an image carousel where each slide has a different duration and the carousel stops on the last image. Follow-up: show a countdown on each slide, auto-advance to the next image at 0, and stop at the end. The countdown is the hard part — use `setInterval` inside `useEffect`.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/image-carousel?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Shuffle and deal a set of 5 cards. The tricky part is the animation: reveal cards one by one.

## System design questions

- Design a chat application.
  - [Read answer](https://www.greatfrontend.com/questions/system-design/chat-application-messenger?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- Design Airbnb (travel booking platform).
  - [Read answer](https://www.greatfrontend.com/questions/system-design/travel-booking-airbnb?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)

_Source: [Glassdoor Airbnb Front End Engineer Interview Questions](https://www.glassdoor.sg/Interview/Airbnb-Front-End-Engineer-Interview-Questions-EI_IE391850.0,6_KO7,25.htm)_

## Algorithm

Airbnb does have rounds evaluating your Computer Science fundamentals by asking LeetCode-style questions. Do be prepared for them.

## Insider tips from the GreatFrontEnd community

These tips were shared by [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) users who have completed interviews with Airbnb.

**8th Jan 2026**:

> My experience with Airbnb for the screening round (Payments team). I was asked to build an image carousel where each slide has a different duration, and the carousel should stop on the last image — they give you the image dataset. The follow-up was to show a countdown on each slide.
>
> What they were looking for:
>
> - Speak out loud while thinking or writing code (I was working in silence and that hurt).
> - Discuss your approach beforehand. They will give you hints if you go in the wrong direction.
> - Make no mistakes — they kept asking why I did each thing.
> - Maybe completion of the follow-up also counts (I couldn't finish the countdown in time).
>
> The countdown is the hard part — brush up on `setInterval` inside `useEffect`. Setup was a React project.

**23rd Oct 2025**:

> Adding to this Airbnb thread: I got asked none of the tagged questions. I was given the image carousel — the interviewer kept adding features until time ran out. Definitely brush up on the `useEffect` hook if you're prepping.

**21st Mar 2025**:

> "Our frontend technical screens tend to be more practical than algorithmic".... proceeds to drop a LC hard question during the screen FML
>
> Not my first rejection but actually wanted to work at Airbnb for a long time now so this one just hurts a bit more. I actually learned a good amount using GreatFrontEnd to prepare so I definitely did improve.

**12th Jul 2024**:

> Just got done, it was okay. They asked Backbone.js, but the 2nd part was slightly different from GreatFrontEnd. Threw me off quite a bit. Got the right output, but took up the whole time. Let's see! Not feeling super confident based of the interviewer's demeanor
>
> It was add on listener, but the event names are change:foo, change:bar, (which is fine).
>
> There was additional on change which should be a global change listener that fires when any change is made
>
> And the kicker was that when you call unset, you need to keep the listeners (soft delete the data), so that when you set the attribute again, all the global listeners and the attribute listeners before unset are fired

**19th Apr 2024**:

> I had the airbnb onsite and thought I had done great on the FE architecture round just to hear from the recruiter the feedback was negative. I'm usually good at predicting the outcome of interviews but honestly this one puzzles me. Question was to design a chat, nothing fancy. Interviewer never showed signs of disagreement or even contested my design decisions. Recruiter won't share more details....

**16th Apr 2024**:

> Had my first technical round with Airbnb, did all Airbnb tagged problems on GreatFrontEnd except the Backbone Model one. Guess which one they gave me lol all good though, I managed to solve the problem with time to spare, I’m pretty sure I did enough to make it to the next round but it’s hard to tell in these times.

For more insider tips, visit [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook)!
