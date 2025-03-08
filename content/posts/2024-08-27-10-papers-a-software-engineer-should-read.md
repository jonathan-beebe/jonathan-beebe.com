---
title: 'Ten Papers a Software Engineer Should Read'
date: '2024-08-27'
tags: 
  - software-engineering
  - technology
---

There’s no such thing as “self-taught.”

Self-directed, maybe. But not self-taught.

As someone who didn’t learn software engineering through a university, I am deeply indebted to those who came before me and wrote about what they learned. I developed my career largely from reading others’ work. They were my teachers.

Below you will find a rather personal list of essays that have shaped my career, leading up to my current role as a Director of Engineering for a fintech product. These documents explore some common threads which I have found to be essential as I build out a world-class product team.

Growing a continuous learning culture, with effective application of learning.

Creating and leveraging rapid feedback loops.

Aiming at simplicity, managing complexity, and avoiding anything unnecessary.

Growing code that evolves over time to accommodate new learnings about our customers, product, and industry.

Creating quality that allows a team to enjoy working in our code year after year; this isn’t perfect code, it’s enjoyable code.

### 1\. The Quality Without a Name

This essay has influenced my career more than any other. It has shaped the kind of output I strive to create: code that is enjoyable to work in. If you enjoy well-crafted metaphors that unlock new perspectives on your craft, then I highly recommend this essay.

The Quality Without a Name, an essay by Richard P. Gabriel found on page 33 of his book [Patterns of Software](https://www.dreamsongs.com/Files/PatternsOfSoftware.pdf)[, available as a free PDF here](https://www.dreamsongs.com/Files/PatternsOfSoftware.pdf).

### 2\. Ball of Mud

Standing at the opposite end of the spectrum to Richard’s essay, this article gives a name to the lack-of-quality that none of us wants to live with: a big ball of mud. It explores the forces that cause us to create balls of mud and then to remain stuck in the muck. It discusses the negative feedback loops that lead to ever-increasing decay. And it discusses the cure, the positive feedback loops that generate ever-refined code as our understanding of the problem evolves.

[Big Ball of Mud](http://www.laputan.org/mud/mud.html) was written by Brian Foote and Joseph Yoder.

### 3\. No Silver Bullet

This is the seminal article by Frederick P. Brooks, Jr. He explores how the thinking that goes into understanding the problem is the hard part of software, not the writing of the code. In my experience this observation holds true. Complexity comes from conceptual errors, and there is no easy way out of this conundrum. This is the hard work of software engineers.

You can find the [original scan here](https://www.cs.unc.edu/techreports/86-020.pdf) and a [cleaner copy here](http://worrydream.com/refs/Brooks-NoSilverBullet.pdf).

### 4\. Out of the Tar Pit

This paper adds to the conversation from No Silver Bullet, discussing several approaches to eliminating accidental complexity. Simplicity is hard. Complexity begets more complexity. The harder a system is to understand, the harder it will become to understand. Nevertheless, we must aim for simplicity.

Out of the Tar Pit, by Ben Moseley and Peter Marks, [available as pdf here](http://curtclifton.net/papers/MoseleyMarks06a.pdf).

### 5\. On Designing and Deploying Internet Scale Services

James Hamilton of Microsoft shows us how to grow an always-on and always-available digital product, with lessons learned from the Windows Live services platform. His paper revolves around three core tenants.

Expect failures.

Keep things simple.

Automate everything.

I appreciate the human aspects of this paper. Creating operations-friendly services that can recover from failures automatically means the people supporting it aren’t interrupted. If they are with their families, they stay with their families. If they are asleep, they stay asleep. Not only is this a great business practice, it’s also a great way to treat your team.

On Designing and Deploying Internet Scale Service by James Hamilton is [available as pdf here](https://mvdirona.com/jrh/TalksAndPapers/JamesRH_Lisa.pdf).

### 6\. Non-atomic Refactoring and Software Sustainability

This paper challenges the concept of what it means for software to work. Just because code can compile and run today doesn’t mean it works. If your code isn’t able to change and adapt to an unknown future, or if it unexpectedly fails to work tomorrow, then it doesn’t fully solve the problem. It doesn’t work. Sustainable software continues to work over time, in response to continuous learning and continuous changes.

By Titus Winters of Google, [available as a pdf here](https://abseil.io/resources/wapi18-winters.pdf).

### 7\. On the introduction of “tech debt”

Ward Cunningham introduced the metaphor of “technical debt” in a short article from 1992 entitled The WyCash Portfolio Management System.

Exploring the origin of this metaphor is useful, if only to ask yourself, does your use of this idea unlock original and useful thinking, or is it a crutch suppressing your thinking. A careful reading of who the audience was, why he introduced the metaphor, and what he meant by it, reveals much about the quality of his thinking back then, and our weaker use of the metaphor today.

Read [The WyCash Portfolio Management System](http://c2.com/doc/oopsla92.html) [here](http://c2.com/doc/oopsla92.html).

### 8\. Searching for Build Debt: Experiences Managing Technical Debt at Google

I include this in concert with Ward’s paper above. In this essay engineers from Google discuss a principled approach to technical debt in one of their systems at scale. In one sense, this is a practical exploration of how to address the knowledge gap between what we knew back when we created our code, and what we know now and want to be represented in our code. The article also explores unanticipated consequences. For example, addressing technical debt can often reveal more of it, and the blast radius of new learning can have ripple effects.

[Available at Google Research](https://research.google/pubs/pub37755/).

### 9\. Source Code Rejuvenation is not Refactoring

This paper discusses another aspect of keeping your code fresh, free from rot and decay.

I found this article to be useful in separating two concerns. The first, which can be roughly bucketed into refactoring, is rewriting code to accommodate new understanding. The second, rejuvenation, is keeping up with the technology curve as it evolves over time. Refactoring ensures your code continues to solve your product problem. Rejuvenation keeps your code modern.

This one hit home as a mobile developer, especially within iOS. Apple updates and modernizes their tool set every year, like clockwork. To keep an iOS mobile app working one must sync with this cycle, or risk decay so severe an app may not compile or run within a year or two. There is an annual rejuvenation cycle inherent in an iOS app.

[From Peter Pirkelbauer, Damian Dechev, and Bjarne Stroustrup of Texas A&M University](https://stroustrup.com/sofsem10.pdf).

### 10\. Triple Entry Accounting

Today any fintech engineer can expect questions about cryptocurrency and the blockchain, so you might as well be prepared. This paper is the origin of the blockchain. My favorite line is from the abstract, “This system creates bullet proof accounting systems for aggressive uses and users.” Aggressive indeed.

[The paper that opened the door to cryptocurrency](https://iang.org/papers/triple_entry.html), by Ian Grigg.

### 11\. Learning, U.S. Marine Corps

I know, I said ten papers. I also said this was personal, and underneath all of these is my deep need and desire to be a lifelong learner, and to cultivate a community of learners around me. If that resonates with you then you may like this document.

At number 11, this isn’t a tech paper. This document covers continuous learning, an essential concept if you want to create a product, team, and business that can evolve and remain relevant in the ever changing landscape of an uncertain future.

It discusses the nature of learning, the culture of learning, the learning environment, and finally the learning leader.

[Learning](https://www.marines.mil/Portals/1/Publications/MCDP%207.pdf?ver=2020-03-03-111011-120) [is available as pdf directly from the U.S. Marine Corps](https://www.marines.mil/Portals/1/Publications/MCDP%207.pdf?ver=2020-03-03-111011-120).