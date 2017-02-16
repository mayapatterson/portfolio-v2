---
layout: page
title: Redesigning Trunk Club's Onboarding Experience
image_path: /images/illustrations.png
preview: How we improved Trunk Club's user experience for first time customers and increased conversion through a sign-up redesign.
time: 8 min read
---



![onboardingHero](/images/onboardingHero.png)





## Problem

Trunk Club recognized we needed to do a better job at getting our new users onboarded onto our service. We were not meeting user's expectations during the sign-up funnel, which meant important metrics like account creation and member conversion were greatly suffering.



## The team

I served as design lead on a team of front and back-end developers, two PMs, and a few designers.

![old_womens_flow](/images/oldOnboardingFlows.png)

## Product background

Our service relies on getting new users through our onboarding funnel and getting them connected to their Trunk Club stylist. Our onboarding process wasn't supporting this need.

From a design and technical perspective, the onboarding experience was outdated, inconsistent, and ultimately wasn't a positive reflection of our brand. The women's experience used an entirely different set of visual design elements in comparison to our men's flow. The men's experience had barely been touched for two years. Furthermore, our onboarding application was technically archaic, making it difficult for the team to iterate and test new concepts.

We understood that redesigning and rebuilding the entire onboarding experience for Trunk Club was an enormous undertaking. However, a strong onboarding experience for our users was instrumental to Trunk Club's success as a growing business and our user's happiness.



## Important metrics

- Conversion - turning new leads into customers
- Connection rate - connecting new leads to their assigned stylist
- Taker rate - how often new leads take a first trunk
- Keep rate - how many items do new customers keep from their first trunk




## User research 1.0

We began by hosting user research sessions to understand how our users felt about the current onboarding flow. A mix of designers, developers, and product managers were involved in the session. We recruited participants to come into our office and test out our onboarding flow. Here's what we learned:

- Our users had no idea that they would be connected to a stylist, a real person, at the end of onboarding.
- Users didn't yet trust that their stylist was right for them
- Users expected to be asked style questions, lifestyle questions, and personal information
- Our branding and visual assets caused our target audience to turn away




**User research with our stylists**

Trunk Club has hundreds of stylists powering our service. We interviewed five stylists to understand how they were using new lead's onboarding information. This would help inform what bits of information we might need to add or remove from our flow.

In short, we learned that they weren't using any of the information that our user's gave during sign-up 😭. Stylists felt overwhelmed by the way we presented new user information to them. This resulted in our stylists **creating another onboarding for their new leads** by sending them dense style surveys via email. This workflow is not only unproductive for stylists, but resulted in a clunky and unenjoyable experience for our users.



**What is success?**

After synthesizing our learnings from the first round of user research sessions, we decided to document a list of priorities for our new design. I sat down with the lead product manager (hi, Nick 😃) to create a list of criteria to measure our new designs against. Here's a summary of what we came up with:

We're doing a good job if...

- The member has a clear expectation that they are assigned a personal stylist (that is a real person).
- The member is able to choose how and when to communicate with their stylist, including talking right away.
- The conversation drives towards an actual trunk that the member will receive.
- Answering questions about your style and your needs is fun (if you’re the type of person that enjoys that type of thing, anyways).
- Answering questions about your style feels like it will improve your experience with Trunk Club.
- The member’s profile informs—and compliments—the conversation between stylist and member.
- The member’s profile improves the personalization of our product experience.
- The member’s profile informs our segmentation for marketing and merchandising.
- Stylists are not emailing long, arduous “style questionnaires” instead of connecting with the member for a conversation.


Over time as we began implementing design solutions, items on this list developed into new projects that we worked into the team's future roadmap.



### Ideation###

Now it was time to begin designing solutions for our onboarding experience. We wanted to explore broad provocative solutions, as well as near-term improvements the dev team could get started on.



**Near term solutions**

Based on research, I understood that we were not asking our leads enough information about their clothing preferences and needs. This resulted in lack of trust from our leads and didn't enable our stylists to serve their new leads effectively.

I started by sketching additional questions we were not currently asking our leads. An improved "style section" and an invention of a budget question were two major areas of opportunity for our onboarding to bring delight and increase trust with our users.

[insert solutions]



### Exploratory Prototyping###

Although we knew what additional questions we believed our onboarding process needed to include, we weren't sold on the UI and overall flow. Through rapid ideation and prototyping, we pushed ourselves to design a provocative onboarding experience. One that was entirely different from our current onboarding flow.

**Introducing, TrunkBot**

Our logged-in members use messaging to communicate with their stylist, but what if we extended that experience to new users? Could we even use a bot to onboard users efficiently and connect them with their stylist, thereby teaching the user how to use our product while signing up? Or, was a more traditional UI with buttons and forms more suitable for our users' goals?

Our team rallied behind testing a bot-based onboarding. I've already written about the details of my design process for that test here (insert link to medium post). In short, the bulk of the design took shape within a script. My main objective was to build a quick scrappy prototype that would garner the insights we needed.

[insert images of bot onboarding and script]

We learned:

*...that the bot onboarding felt like it required too much work [for our participants], when in reality it took half the time our normal onboarding takes. Participants gave feedback that messaging with a bot wasn’t intuitive, which caused them to feel overwhelmed. They expressed desire to fill out their preferences through a more traditional survey.*

We also gained several extremely important insights from that prototype test that influenced my next prototype

## Takeaways

- **Provide a narrative** with a clear finishline to understand why I am giving Trunk Club this information
- **Optimize the UI** for our audience who don't find much joy in tech trends.
- **Enhance the fun stuff** by allowing users to tell us about their style and respond to clothing
- **Don't make the flow too short ** as  we’ve seen a loss of trust and understanding in all of our user tests when we try to shorten the experience




### Design Refinement###

Based on the findings from our previous two user tests, we decided to return to a more traditional flow. However, we made it a requirement to set expectations throughout this new experience. We hypothesized that adding additional context to help form expectations, trust, and delight, would improve our user’s onboarding experience.

We wanted to understand whether a narrative-focused onboarding foster trust, build expectations, create a warm handoff, and be delightful for our users?



I challenged myself to use Framer as the prototyping tool of choice. This was a new tool for our team and one I desperately wanted to learn. The designs focused on setting expectations through copy, visual queues, and a little animation. Here's what we tested:

http://share.framerjs.com/6hpshdj725ca/

http://share.framerjs.com/o6be17qm196q/



**A success!**

[Insert pic of me smiling next to sticky notes]

Overall, a narrative-focused onboarding was very well-received by our participants. The design set expectations early on for users, which drastically decreased confusion and increased delight at the end of the sign up process. Participants verbally expressed their content with the experience multiple times during the process.

All of our participants understood why they were put into a messaging interface after onboarding and, knew their stylist was a real person. This was a major improvement in comparison to our current experience, where users have very little understanding of what to do post-signup.



**Time to build the thing**

With the help of my PMs, we broke the prototype down into pieces of work that the developers could fit into their sprints. Because we received most of our onboarding traffic on mobile web, we focused our efforts on that experience. I partnered with a front-end developer (S/O Zach 😜) as he built out the flows, interactions, and UI elements of the onboarding experience.

As I supported the development process, I also partnered with creative to ensure the onboarding visual design styles reflected that of our recently re-branded tc.com page.



**Optimizing our stylist experience**

One of our goals was to eliminate the second round of onboarding our stylists put new users through. I worked with our sales team (the tech team who builds our stylist's tools) to create a scrappy near-term solution.

[insert pictures of member account]

[insert stylist quotes about new feature]

That small design improvement drastically improved our stylist's ability to better service new leads.



**Our failures**

After launching our men's and women's flow, we quickly received results that our new experiences weren't increasing lead sign-up conversion metrics. So we dug in deep. I helped analyze the GA funnel with my PMs (thanks, Oddie for teaching me 🙌🏽) and proposed iterations to further optimize areas in the experience that weren't strong.

We eventually rolled out our women's onboarding after minorly increasing our visitor-lead conversion. However, our men's was still suffering. We ended up rolling back certain design improvements in an effort to get this experience up to parity.

After exhausting all design improvement, our development team buckeled down to really understand where our experience was failing. This was a long and tedious process, but guess what we found...



**WE WON!!**

…and I mean big time. Zach discovered that our analytics tools were misinterpreting our results. Our men's onboarding increased conversion by **over 20%**. And it had probably been winning for a while.

There's no way to know how much our women's design performed since we fully rolled it out before discovering this error. However, we all agree that it is highly likely that it increased conversion at a similar rate.



**Where we are now**

Because our team took a risk and rebuilt our onboarding application, we are now able to tweak, add, and test new questions to our onboarding flows. Furthermore, our iOS flow is slotted to launch shortly.

Our team now focuses on iterating and testing new questions we believe optimize our customer's experience. Recently, we added a new question to the flow that asks users for their budget (remember that near term design I told you about). That one question has **increased our member conversion by 23%**!

We've learned that adding (relevant) questions to our onboarding process is a win-win for TC and our users. When our sign-up process is too short our user's don't trust that we can provide them with good service. Furthermore, if we collect more information upfront, our stylists can focus on packing trunks quickly versus spending time asking our leads more questions about themselves.

Here's to better onboardings for all!
