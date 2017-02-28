---
layout: page
title: Redesigning Trunk Club's Onboarding Experience
image_path: /images/casestudyOnboarding.png
preview: How we improved Trunk Club's user experience for first time customers and increased conversion through a sign-up redesign.
time: 8 min read
---


![onboardingHero](/images/onboardingHero.png)



When users visit Trunkclub.com they want to receive clothes and styling advice. The onboarding process must allow them to easily provide information about their style preferences to get started with the service. A total redesign and a new codebase provided new members with a delightfully simple sign-up experience while increasing conversion rates.



## Problem

when new users sign up for Trunk Club, they are connected with a personal stylist who will send them a trunk of clothes based on their needs. Over 50% of new Trunk Club users weren't being connected with their stylist. From a design and technical perspective, the onboarding experience was outdated, inconsistent between men and women, and didn't reflect our brand. From a technical perspective, the codebase was outdated making it difficult for the team to iterate and test new concepts.

A strong onboarding experience proved necessary to Trunk Club's success as a growing business and our user's happiness.



## The team

I served as design lead on a team of front and back-end developers, two PMs, and a few designers.

![old_womens_flow](/images/oldOnboardingFlows.png)



## Project scope

Although the onboarding process doesn't end until a user's first purchase, the scope of this work focused on optimizing the experience of the sign-up process. The new experience would be implemented across all platforms (mobile web, desktop, iOS, and Android), but we focused on web first due to the large percentage of traffic on those platforms.


## Important metrics

- Overall conversion - turning new leads into customers
- Connection rate - connecting new leads to their assigned stylist
- Taker rate - how often new leads take a first trunk
- Keep rate - how many items do new customers keep from their first trunk




## The Design Process

Through the support of my team and PM, I encouraged our team to leverage user research and testing to validate any solutions we designed. We also wanted to explore provocative solutions as well as near-term solutions.


### Understanding the why with user research

We began by hosting user research sessions to understand how our users felt about the current onboarding flow. We recruited participants to come into our office and test out our current onboarding flow. Here's what we learned:

- Our users had no idea that they would be connected to a stylist, a real person, at the end of onboarding.
- Users didn't yet trust that their stylist was right for them
- Users expected to be asked style questions, lifestyle questions, and personal information
- Our branding and visual assets turned off our target audience


> our goal was to create an onboarding process that resulted in a nautral handoff to a member's assigned stylist.



## Focused Ideation

We wanted to explore broad provocative solutions, as well as near-term improvements that we could implement in the interim.


### Near term concepts

Based on our research we knew new users lacked trust that their stylist could serve them. They felt that there wasn't enough information collected about their style needs and preferences. We explored new flows to test different sections within the sign-up experience.

![whiteboardBrainstorm](/images/whiteboardBrainstorm.jpg)



Because we wanted to rapidly test our near term explorations I jumped into Sketch to flesh out new questions that we would inject into the prototype.

![neartermMocks](/images/neartermMocks.png)

I explored asking our user's for their names upfront to make the flow feel more personalized.

![neartermName](/images/neartermName.png)

We also knew our current women's style questions were majorly off brand and heard feedback from users that the images didn't represent a service they would use. I brought in updated imagery along with new ways to ask women about their style

![neartermStyle](/images/neartermStyle.png)

Other explorations included questions about clothing budgets, the ability to opt out of sizing questions (arguably the most sensitive and dense portion of our sign-up flow), and a reduced account creation page that didn't ask new users for sensitive information like phone number.

![neartermOther](/images/neartermOther.png)



I partnered with a designer who built a quick HTML/CSS prototype, while I continued to flesh out our guide and goals for the user test. We focused on the mobile web experience since that's where we see a majority of new traffic.

[Check out the prototype we tested](https://tc-signup.firebaseapp.com/) (but remember it was designed for a mobile device)


### Findings
After testing the near-term design with participants, we gained several insights:

- New user's tolerance for answering more questions is higher than we expected
- Users still didn't understand why they were paired with their stylist
- Asking for someone's name too early in the process causes hesitation to continue
- UI and copy refinements were needed for our budget and style questions


## Exploratory Ideation

After validating some of our assumptions with the near-term concept, we decided we weren't sold on the UI and overall flow. We removed the constraint that was a step by step survey-like signup flow — a UI we always used for our sign-up experience. Maybe we could address our user's lack of trust and understanding of their stylist by using a more provocative solution.


### Divergent Thinking

I brought together a group of designers, developers, PMs, and a few folks outside of the tech team to generate a broad set of concepts. We used the findings from the previous research sessions to document a list of attributes we felt best exemplified a great onboarding experience for Trunk Club.

We used the context of a conversational experience to think through solutions, as Trunk Club strongly believed in the power of 1:1 relationships. I mean, our entire logged-in experience was driven by a messaging application!

![conversationSketches](/images/conversationSketches.png)



### Introducing, Trunkbot

Our logged-in members use messaging to communicate with their stylist, but what if we extended that experience to new users? Could we even use a bot to onboard users efficiently and connect them with their stylist, thereby teaching the user how to use our product while signing up?

Driven by our group sketch session, we believed a bot could provide the natural handoff from Trunk Club's homepage to their personal stylist that our current onboarding lacked.

![botScript](/images/botScript.png)

My design efforts were focused on the script and flow. Designing an experience through words was new for me and the rest of the tech team, but we were more than thrilled to test a bot.

![botFlow](/images/botFlow.jpg)

Finally, using Slack's prototype for their bot as inspiration, I hacked together our internal tools to create a prototype inside of our existing messaging application.

![botPrototype](/images/botPrototype.png)



I wrote about the process of designing and testing this experience [here](https://medium.com/unpacking-trunk-club/trunkbot-or-not-f9443e8f44b5#.xcamb2p9z) but in short this is what we learned:

*...the bot onboarding felt like it required too much work [for our participants], when in reality it took half the time our normal onboarding takes. Participants gave feedback that messaging with a bot wasn’t intuitive, which caused them to feel overwhelmed. They expressed desire to fill out their preferences through a more traditional survey.*


### Takeaways

Although our Trunkbot didn't perform so well, we gained a few valuable insights:

- **Provide a narrative** with a clear finishline to explain why Trunk Club needs this information
- **Optimize the UI** for our audience who aren't wowed by tech trends
- **Enhance the fun stuff** by allowing users to tell us more about their style in engaging ways
- **Don't make the flow too short** as we’ve seen a loss of trust and understanding in all of our user tests when we try to shorten the experience


## Design Refinement

After pushing the limits of our sign-up flow UI. we decided to return to a more traditional flow as it better suited our user's goals. However, we made it a requirement to set expectations throughout this new experience. We hypothesized that adding additional context to help form expectations, trust, and delight, would improve our user’s onboarding experience.

I challenged myself to use Framer as the prototyping tool of choice. This was a new tool for our team and one I desperately wanted to learn. The designs focused on setting expectations through copy, visual queues, and a little animation. Here's what we tested:

http://share.framerjs.com/6hpshdj725ca/

http://share.framerjs.com/o6be17qm196q/




![narrativeSuccess](/images/narrativeSuccess.png)

### A success!

Overall, a narrative-focused onboarding was very well-received by our participants. The design set expectations early on for users, which drastically decreased confusion and increased delight at the end of the sign up process. Here's a few quotes from our participants:

> "This is pretty cool, it's telling me about the broad categories that I like. You also get the option to skip, which is pretty cool…I would expect to see this"
>
> "This is actually better than what I was expecting. It might overwhelming if you break it down too much on this first step"
>
> “Elegant. Simple. Very straightforward and the design is excellent.”

All of our participants understood why they were put into a messaging interface after onboarding and, knew their stylist was a real person. These were all big wins for our sign-up flow.


## Now, we build

With the help of my PMs, we broke the prototype down into pieces of work that the developers could fit into their sprints. We would start with mobile web and desktop, then our native platforms. I partnered closely with a front-end developer (whatup Zach 😜) as he built out the flows, interactions, and UI elements of the onboarding experience.

As I supported the development process, I also partnered with creative to ensure the onboarding visual design styles reflected that of our recently re-branded trunkclub.com homepage.


### Our failures

After launching our men's and women's flow, we quickly received results that our new experiences weren't increasing lead sign-up conversion metrics. So we dug in deep. I helped analyze the GA funnel with my PMs (thanks, Oddie for teaching me 🙌🏽) and proposed tweaks to the flow. I also used Inspectlet to review real users signing up, which exposed bugs and needed UI refinements.

We eventually rolled out our women's onboarding after minorly increasing our visitor-lead conversion. However, our men's was still suffering. We ended up rolling back certain design improvements in an effort to get this experience up to parity.

After exhausting all design improvement, our development team buckeled down to really understand where our experience was failing. This was a long and tedious process, but guess what we found...


## WE WON!!

…and I mean big time. Zach discovered that our analytics tools were misinterpreting our results. Our men's onboarding increased conversion by **over 20%**. Our new experiences had been winning, and they had been for a while.

[insert mocks of desktop]

There's no way to know how much our women's design performed since we fully rolled it out before discovering this error. However, we all agree that it is highly likely that it increased conversion at a similar rate.


### Where we are now

Because our team took a risk and rebuilt our onboarding application, we are now able to tweak, add, and test new questions to our onboarding flows. Furthermore, our iOS flow is slotted to launch shortly.

[insert iOS mocks]

Our team now focuses on iterating and testing new questions we believe optimize our customer's experience. Recently, we added a new question to the flow that asks our new women user's for their clothing budget. That one question has **increased our member conversion by 23%**!

We've learned that adding (relevant) questions to our onboarding process is a win-win for TC and our users. When our sign-up process is too short our user's don't trust that we can provide them with good service. By using micro-copy, fine tuned questions, and delightful visuals, we've enhanced the overall user experience and significantly improved Trunk Club's conversion rates.

Here's to better onboardings for all!
