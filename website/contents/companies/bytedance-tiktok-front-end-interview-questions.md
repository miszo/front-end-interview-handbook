---
title: ByteDance/TikTok Front End Interview Questions
sidebar_label: ByteDance/TikTok interview questions
description: Master TikTok frontend engineer interviews with real coding questions, UI components, algorithms & insider tips from successful candidates.
---

:::info Latest version on GreatFrontEnd

Find the latest version of this page on [GreatFrontEnd's ByteDance Front End Interview Guide](https://www.greatfrontend.com/interviews/company/bytedance/questions-guides?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook).

:::

ByteDance/TikTok's front end interview is quite balanced in terms of interview format.

## JavaScript coding questions

- Implement `Promise.all`.
  - [Practice question](https://www.greatfrontend.com/questions/javascript/promise-all?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Implement a function which extends `Array.prototype`.
  - [Practice questions](https://www.greatfrontend.com/questions?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook)
- Implement a polyfill of `Function.prototype.bind` — handle the `new` keyword correctly.
  - [Practice question](https://www.greatfrontend.com/questions/javascript/function-bind?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- Implement Map Async Limit (the "solution 4" variant — async-iterator-based, not just Promise.all chunking).
  - [Practice question](https://www.greatfrontend.com/questions/javascript/map-async-limit?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Implement a `compose` middleware function so that async middlewares like Koa-style `f1`, `f2`, `f3` (each calling `next()`) execute in the correct nested order.
  - [Practice question](https://www.greatfrontend.com/questions/javascript/compose?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- React-like VDOM but instead of creating DOM nodes, output an HTML string given an input object with `type` and `attributes`.
- JavaScript quiz: given a list of Promises with console statements, determine the order they will print.

## User interface coding questions

- Implement a dropdown component.
  - [Read answer](https://www.greatfrontend.com/questions/system-design/dropdown-menu?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- Implement a transfer list component (move items between two lists with select-and-shift). Note: TikTok interviews on Lark, which doesn't render React — you code in a Node.js env without being able to test live UI, so write clean markup and explain as you go.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/transfer-list?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)

## System design questions

- Project deep-dive design round (~50 minutes): walk through one of your past projects, draw a flowchart of the workflow, and discuss potential improvements. Be ready to explain why you want to join TikTok.

## Quiz questions

- Difference between `localStorage` and cookies.
  - [Read answer](https://www.greatfrontend.com/questions/quiz/describe-the-difference-between-a-cookie-sessionstorage-and-localstorage?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)

## Algorithm

- Merge two sorted integer arrays, remove duplicates.
- You have an image on a page, write css and js so that when mouse is over the image, it rotates 180 deg with 1 sec animation.
- Given a list of points, find out if any four of them form a square. Return 'true' if possible, else 'false'.
  - Examples: `[[0, 0], [2, 0], [1, 1], [0, -1], [-1, -1], [0, 2], [0, 1], [1,0]]` -> `true`
- Check for balanced brackets in a string.
- Given two nodes, return the section of the tree between these two nodes.
- Find the islands in a grid of land and sea.

_Source: [Glassdoor ByteDance Front End Developer Interview Questions](https://www.glassdoor.sg/Interview/ByteDance-Front-End-Developer-Interview-Questions-EI_IE1624196.0,9_KO10,29.htm)_

## Insider tips from the GreatFrontEnd community

These tips were shared by [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) users who have completed interviews with ByteDance/TikTok.

**8th May 2026**:

> Just wrapped my 4th round with a technical manager at TikTok: more projects/resume grilling, heavy on trivia, UI coding, slightly behavioral but more so testing your engineering thinking than collaboration. The TM's general advice was that for new grads, big project experience isn't strictly expected — they're evaluating thought process. Basically know every tech you put on your resume inside and out, and be able to talk about coding with AI.
>
> Also: being able to speak Chinese for the non-technical parts of the interview definitely helped with rapport, even if you do the technical portion in English.

**16th Apr 2026**:

> TikTok loop for me was projects/resume grill, basic system design + trivia, and an algorithms question. No behavioral round in the early loop. They're pushing AI in almost every aspect of the product, so expect questions around it.

**17th Nov 2024**:

> cant say too much because of NDA but this is how it went for TikTok entry level FE
>
> 1. leetcodes, javascript fundamentals (covered in GFE 1 month study plan)
> 2. UI component + follow up
> 3. system design based on past project + javascript coding and now awaiting 4th round w recruiter
>
> feedback for each round was fairly quick, received update the next morning

**12th Nov 2024**:

> i do bytedance/tiktok round 2 recently, unfortunately get rejected. the coding questions is quite overwhelming for me. after experience & quiz questions, the interviewer directly give me 3 questions (all for ~30 mins), and i can choose the order.
>
> 1. similar to Map Async Limit but has to be solution 4
> 2. some compose middleware question (can't find anything similar)
> 3. implement bind, but i can't handle the new keyword

**21st Oct 2024**:

> just finish my third rounds interview with TikTok. it's a design round with 50 mins deep dive on my pervious project and potential improvement. have to draw a flowchart to demo the workflow. overall it's really conversation heavy. and also asked why you want to join TikTok. don't think I am going to pass this round but Good Luck to whoever interview later! 🙏

**8th Aug 2024**:

> Had my first round tiktok frontend engineer interview. Not sure on the level but I told them I have 3 YOE so maybe 2-1? Strange interview tbh. There was a huge language barrier and it was difficult to build rapport with the interviewer (my interview was at night so I had someone overseas). Very difficult to read. First 20 minutes was talking about past projects/experiences/challenges, then a React coding question, then a JS quiz question, and then an untagged tiktok LC med... I asked some good questions about the company imo but the interviewer could barely answer it. I tried my best but it was not a collaborative interview at all and more of a test so it was challenging for me. I think it was a lot for an hour and we ended up going over time

For more insider tips, visit [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook)!
