---
title: Microsoft Front End Interview Questions
sidebar_label: Microsoft interview questions
description: Microsoft coding round questions & system design interview prep. JavaScript, React, DOM concepts + real candidate experiences and insider tips.
---

:::info Latest version on GreatFrontEnd

Find the latest version of this page on [GreatFrontEnd's Microsoft Front End Interview Guide](https://www.greatfrontend.com/interviews/company/microsoft/questions-guides?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook).

:::

## JavaScript coding questions

- Tic-tac-toe implementation using vanilla JavaScript, HTML and CSS.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/tic-tac-toe?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Create a chat interface like Microsoft teams.
- Use OOP to implement a Chess game.
- Implement a number/character pad like old flip phones — buttons where `2 = abc`, `3 = def`, etc. Pressing the same key cycles through letters within a short time window; after a delay, the next press appends. e.g. press 2 → `a`, press 2 again → `b`, wait 1s and press 2 → `ba`, press 6 → `bam`.
- Design an SDK in JavaScript implementing features like throttling and retry strategies. Focus on defining contracts that consumers will adhere to.
  - [Practice question (throttle)](https://www.greatfrontend.com/questions/javascript/throttle?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Rabin-Karp string-matching DSA problem (recurring at Microsoft).

## User interface coding questions

- Create a notification interface like Microsoft teams.
- Image slider implementation.
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/image-carousel?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Build a basic to-do app in React (Add / Remove / Edit).
  - [Practice question](https://www.greatfrontend.com/questions/user-interface/todo-list?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- Build a React address-book app: simple form with a basic backend provided, then extend to fetch and load more entries using a pagination token.

## Quiz questions

- What is a prototype?
  - [Read answer](https://www.greatfrontend.com/questions/quiz/explain-how-prototypal-inheritance-works?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- What is a closure?
  - [Read answer](https://www.greatfrontend.com/questions/quiz/what-is-a-closure-and-how-why-would-you-use-one?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- What is the difference between `let`, `const`, and `var`?
  - [Read answer](https://www.greatfrontend.com/questions/quiz/what-are-the-differences-between-variables-created-using-let-var-or-const?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Free)
- What is DOM?

## System design questions

- Design an email client like Microsoft Outlook.
  - [Read answer](https://www.greatfrontend.com/questions/system-design/email-client-outlook?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- Design a part of Microsoft Teams (open-ended, you can deep-dive frontend or backend).
  - [Read answer](https://www.greatfrontend.com/questions/system-design/chat-application-messenger?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) (Paid)
- Design a to-do list application (Microsoft 365 team variant).

_Source: [Glassdoor Microsoft Front End Developer Interview Questions](https://www.glassdoor.sg/Interview/Microsoft-Front-End-Developer-Interview-Questions-EI_IE1651.0,9_KO10,29.htm)_

## Insider tips from the GreatFrontEnd community

These tips were shared by [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook) users who have completed interviews with Microsoft.

**25th Dec 2025**:

> My frontend engineer interview at Microsoft was full of LeetCode, but a friend who interviewed for the Microsoft 365 team had a very different loop — they were asked system design for a todo-list type app, one React coding round, and one LeetCode. So it's very much team-dependent — be prepared for every kind of round.
>
> One thing to watch for: a string-matching question based on Rabin-Karp pops up in Microsoft interviews fairly often (you can find it on GeeksforGeeks). Always ask your recruiter what questions/rounds to expect and prepare accordingly. Microsoft recruiting in general feels pretty random — referrals don't guarantee anything and hiring managers' tastes vary a lot.

**20th May 2025**:

> Honestly my interviews at Microsoft were much more chill than Amazon tbh. I do not mind the LP’s but the amount of dry runs they made me do was shocking. I even wrote assert statements before hand but turns out no execution allowed for Amazon.
>
> MSFT however, everything was smooth.

**8th May 2025**:

> I passed the Senior fe loop for a similar team to Microsoft (Copilot) last year. A team which was working on embedding copilot inside m365 Just a standard interview, system design was just catered to modularizing copilot so it can plug into any app

**25th Apr 2025**:

> I did a senior one in 2024 which is roughly the same loop as Microsoft's SDE II but more emphasis on system design

**31st Jan 2025**:

> Hi! Just wanted to give a huge shoutout to GreatFrontEnd and say thanks for all the amazing work the team is doing! After leaving AWS a couple of months back, I was pretty nervous about the job market and didn’t know what to expect. But with GreatFrontEnd as my best friend (and, honestly, confidant lol) throughout the interview process, I was able to land interviews and offers at multiple companies for senior frontend/full stack roles.
>
> Thanks to you, I either got an offer or made it to the onsite stage at the following companies. In each one, I found some element of my prep from GreatFrontEnd extremely valuable: Vanta, Remitly, Coinbase, Microsoft, Lululemon, TikTok, Google
>
> One thing I did find a bit frustrating in system design rounds, though, was how most companies (Even Microsoft) focused on API design but skipped over more advanced frontend deep dives. I love the depth and deep-dives in the prep material—they really made me a better engineer—even if I didn’t always get to showcase it in interviews.
>
> So grateful for all the support and resources! 🙌 Following up on my earlier thread, I was responding to someone about my experience with Microsoft and thought I’d share it here for the community as well.
>
> I had two separate Microsoft onsites—both for Microsoft Teams and Senior Frontend positions—but they were very different.
>
> First onsite (I received an offer for this): React-based interview – Very easy. It included a 30-minute behavioral round followed by a technical session. The question was more like an implementation of a basic to-do app (Add/Remove/Edit todos). Algorithm round – LeetCode Easy/Medium. Another 30-minute behavioral session followed by coding. Hiring manager round – Behavioral + System Design. This was more full-stack focused, but the interviewer gave me the option to deep dive into either frontend or backend, depending on my preference. However, the initial design needed to be full-stack. The task was to implement a part of Microsoft Teams itself. I really loved the discussion—it was very open-ended and adaptive. JavaScript coding – I was asked to design an SDK in JavaScript, implementing features like throttling, retry strategies, etc. The focus was on defining contracts that others would need to adhere to. It felt more like a mix of system design and coding.
>
> Second onsite (No offer for this): LeetCode Medium – A variation of the 3Sum problem. LeetCode Hard - Still have PTSD from this 😄 LeetCode Medium – More of an implementation-focused merge sort problem. System design + Hiring manager – Focused more on API design; the interviewer didn’t care about frontend deep dives at all.
>
> It’s very difficult to predict Microsoft interviews—they have no set format whatsoever. Really didn’t enjoy the second loop, but they didn’t seem to like me either—so I guess it’s even! 😅

For more insider tips, visit [GreatFrontEnd](https://www.greatfrontend.com/?utm_source=frontendinterviewhandbook&utm_medium=referral&gnrs=frontendinterviewhandbook)!
