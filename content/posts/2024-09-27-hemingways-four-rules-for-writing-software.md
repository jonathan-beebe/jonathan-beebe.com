---
title: 'Hemingway’s Four Rules for Writing [Software]'
subtitle: 'A cheeky riff on the famous author’s rules for writing'
date: '2024-09-27'
---

Hemingway swore by these four rules for writing prose ([source](https://www.wordsthatsing.com.au/post/hemingway-rules)):

1.  Use short sentences
    
2.  Use short first paragraphs
    
3.  Use “vigorous” english
    
4.  Be positive, not negative
    

Adapted for software engineering, they might read:

1.  Use short statements
    
2.  Use pure functions
    
3.  Use descriptive variables
    
4.  Be optimistic, not defensive
    

For Hemingway, a great intro for a story was three short, well honed sentences. While I can’t find a direct source, the consensus view seems to be Hemingway believed there was not a single wasted word in “The Old Man and the Sea”. Now imagine for a moment you could say the same about your best code. Image saying there isn’t a single wasted statement. Not a single wasted function. Not a single unnecessary dependency. Not a single wasted byte of memory or single wasted processor cycle.

Wouldn’t it be wonderful! But we work in environments optimizing for other things. Business constraints hinder us from refining our code to this level of quality.

But imagine for a moment we are able to create like this. Imagine our environment is optimized so we can write code following these rules. What does it look like? How does it feel?

## Use short statements
_**A Farewell to Nested Loops**_

Hemingway taught us _less is more_. Cut complexity. Embrace brevity. Strive for clarity.

When we apply this to our code, every statement communicates the work it is doing and why. A reader easily identifies what it does and how it works. The language features used are appropriate for the task at hand. It is clear how inputs flow in, how the function works, and how results flow out.

This is about striking a balance between overly clever code and overly verbose code. Too clever and it forces the reader into deciphering mode. They must stop and parse obtuse syntax or unfamiliar language features. Too verbose and the reader may struggle, getting lost in the weeds of analysis. When striking the proper balance our code becomes easier to comprehend. The reader easily understands the problem and how the code solves it.

## Use pure functions
_**For Whom the Function Calls**_

Great prose communicates clear purpose. There are no wasted words. No distractions for the reader. Likewise, a great function communicates one clear purpose.

If we wrote our code like this, each function would do one thing and do it well. Each object would contain what it needs, nothing more. Components compose together like Lego bricks. Data flows with logical precision. The shape of the assembled system matches the problem you are solving.

Hemingway’s first rule has two phrasings, one being “use short _first_ paragraphs”. I like this focus for software. I often find projects with disorganized file structures, huge main functions, or bloated app delegates. The entry point is overwhelming. Just opening the project burdens the reader with an overwhelming amount of context. The best projects clearly define and delineate each architectural layer and its purpose. The top level structures are clean and easy to read.

When we strive for this kind of quality, our code becomes easier to comprehend. This benefits the new team member. And it will benefit future you when you come back to this code in 8 months.

## Use descriptive variables
_**The Code Also Reads**_

Software is storytelling. It is a choose-your-own adventure. Your customer is the main character. They and their data are on a journey accomplishing a task. To tell this story well, the phrasing and expression of your code matters. Your variable names encode meaning, action, and intent. Thus function and variable names matter. A lot.

Make sure your code tells the story well. Names are not too short or too long. Interactions are purposeful and make sense. The lexicon matches the problem domain. It is easy for new team members to follow the flow of logic and data.

## Be optimistic, not defensive
_**The Optimist and the Sea**_

Part of a software engineer’s job is creating systems that are resilient. The software continues working even when errors or anomalies occur. This isn’t easy. But great code makes it _look_ easy.

A great example of this is eliminating null values. You can structure code so a value is always defined and can never become null or undefined. This eliminates an entire category of bugs, making your code safe and easy to comprehend. The system needs well defined values, so model it that way.

Another great example is how you might model error conditions. Errors can be treated as anomalies, things that shouldn’t happen. But it’s better to model errors as a natural behavior of the system. Handles errors like any other value. Errors should lead to a predictable and well-designed experience for the customer.

For example, say you want to retrieve a video from the server and display it to the user. You can model a system so if the video retrieval fails, the software acts like, “I never received the expected result, so enter a failure state.” But another way to think about this scenario is to model the failure state as a natural state of the system. Both the video response and error response are reasonable values. They are both displayable resources that can have a well defined interface.

Create code that naturally handles both successful and error states.

## Wrap

Obviously an exercise like this is entirely subjective. Even if you like Hemingway’s rules, you may not have a taste for his literature. In the same way, two different software engineers will write code in different styles. The point isn’t to homogenize how we write code. It is to change your perspective on how you think about _how you think about_ writing code.

You might write code that you feel perfectly expresses the intent of the program. And yet, it won’t appeal to someone else’s taste. They will likely find something they feel is wrong. And that’s ok. The point is simply to reconsider _what makes for amazing code?_ To push yourself to be better. Hemingway had rules to push himself to be a better writer. What rules do you have to help you be a better coder?

***

## 7 Other Things

1.  🤣 A youtube short on [reviewing three lines of code vs reviewing 30,000](https://www.youtube.com/shorts/n0jpmnn4cNI).
    
2.  🤔 One of the most common questions I am asked by non-technical folks is “_how do I more effectively work with software engineers?”_ I have signed up for [this Oct 3rd maven course on “How to Master Technical Literacy”](https://maven.com/p/8f5c8c/how-to-master-technical-literacy-evolving-your-approach?). I am excited to see how they approach this problem. I find it noteworthy they discourage taking a coding class. There are more effective ways to learn how to communicate and collaborate with software engineers.
    
3.  🤩 James Earl Jones reading the raven, [via kottke.org](https://kottke.org/24/09/james-earl-jones-reads-poes-the-raven).
    
4.  🤓 Seven good lessons from a career of paying down tech debt. I especially appreciate “linking tech debt and value delivery.” ([source](https://newsletter.pragmaticengineer.com/p/paying-down-tech-debt))
    
5.  😌 Since working from home I have experienced the incredible value of keeping a tidy house. Keeping my work environment clean is essential from mental and physical health. The same is true of code. There is a certain level of tightness or cleanliness that is necessary in order for the code to feel habitable. ([from Kent Beck](https://open.substack.com/pub/tidyfirst/p/the-life-changing-magic-of-tidying?r=36mfb9))
    
6.  😬 The FTC acknowledges social media companies are unsafe for children and are actively spying on them ([via the FTC website](https://www.ftc.gov/news-events/news/press-releases/2024/09/ftc-staff-report-finds-large-social-media-video-streaming-companies-have-engaged-vast-surveillance)). Also see [last week’s item](https://softwareauthor.substack.com/p/refactor-your-communication-3-tools) about the FBI recommending we all use ad blockers.
    
7.  🙄 Getting through Apple’s app review is like a restaurant asking you to prove you’re actually hungry before they’ll seat you to order food. This week the iPhone camera app Halide, which was just featured in Apple’s keynote, has been [rejected by an App Store reviewer because of its camera permission dialogue](https://mastodon.social/@sandofsky/113181384256449181).
    

* * *

## Parting thought

If you are in tech you might believe everyone is using AI, given the constant barrage of news in this space. But it appears customers are not nearly as engaged. In a thought-provoking piece (originally by Ed Zitron, [summarized by Emmanuel Maggiori](https://www.linkedin.com/posts/emaggiori_the-subprime-ai-crisis-activity-7241796179280162817-8vYB/)) they share:

> Customers of Microsoft's 365 suite ... are barely adopting its AI-powered "Copilot" products, with somewhere between 0.1% and 1% ... paying for the features. One firm testing the AI features is quoted as saying that "most people don't find it that valuable right now."

I’ve noticed this in my own behavior in products that I love and use on a daily basis. Many of my favorite products have released integrated AI features over the past year. I don’t use _any_ of the AI features, and when given the preference I actively disable them. Often they get in the way and slow me down.

It makes me wonder, other than directly using an AI chat tool like ChatGPT, are there any AI integrations that you find useful?

([source](https://www.linkedin.com/posts/emaggiori_the-subprime-ai-crisis-activity-7241796179280162817-8vYB))