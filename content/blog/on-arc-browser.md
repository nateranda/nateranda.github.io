---
title: "on Arc Browser"
date: 2025-07-21
summary: "Is The Browser Company making the right move?"
---

Arc is great. No other browser can hit my preferred paradigm like Arc can, and I just need to accept that. This is a rather popular sentiment among Arc users—Arc can turn casual web browsers into power user fanatics. Over the past few years, Arc has grown a loyal user base that is excited to find new workflows and test out new features fresh off the Browser Company press.

But this buzz has been waning. It is clear to all but the naivest followers that Arc is nearing its final product. It's been over a year and a half since Arc's newest feature set, Arc Max, and the weekly update newsletters resemble less like feature drops and more like security patch notes. And The Browser company has indicated in both subtle and less subtle ways that they have moved on from Arc's rapid prototyping roots.

Recently, The Browser Company has come under fire by its followers for pivoting to a new AI-based product Dia. Many users (and by this I mean _vocal_ users) have felt betrayed, like Arc is being dumped for its flashier and more VC-aligned friend. You can see this in the comments under TBC's soft launch video, [The most powerful ways to "hack" our new Dia browser](https://www.youtube.com/watch?v=JCZUIm4S9QQ):

> Ok but why abandon Arc to create another browser instead of bringing "Dia" into Arc?

> Everything shown in this video is going to get “Sherlocked” by the OS vendors and Dia will die on the vine. Arc had great ideas, I really wish they’d kept iterating on Arc instead of jumping on the hype train.

> Reality check: the browser company was never going to take over a large percentage of the browser user base. Y’all did an exceptional job finding a niche and catering to that smaller base, but trying to make a browser for the average joe is actively killing the user base you’ve worked so hard to build. Please come back to developing arc and stick to where you’ve seen actual success.

I have more complicated feelings about Dia which I'll probably unpack later, but I'm here to talk about TBC's pivot, and more specifically, people's reactions to their pivot. I believe that most of these reactions, while expressed in good nature, are quite misguided.

### Abandoning Arc

The first and most major point of criticism is that TBC is 'abandoning' Arc—and that is true, if you define abandoning a product as stopping the development of new features. But it feels naive to assume every product you use is going to be continually developed even when the company that built it is looking to build something new.

To me, it is perfectly fine that TBC has stopped adding new features. On MacOS, Arc's home platform, the app is finished. Aside from a couple lingering tweaks that bug some users, Arc is just about as good as it can get. The paradigm that Arc was born into has been fully realized: vertical tabs, spaces, pinned tabs, folders, and a command bar-centered interface have all been fleshed out, with added AI features and a mobile companion app on top. I have been with Arc since the private invite days, and I don't see any features that could make Arc better than it is now (apart from some features prototyped in Dia, but that's for another day).

To me, the writing on the wall is that Arc dug itself into a niche that its parent company thinks it can never get out of. Not many people use Arc, but those who use it _love_ it. This creates an audience of power-users who couldn't imagine using anything else. While this is great for a product that users pay for, it doesn't quite work for a web browser. I quite like the way that TBC put this in their _[Letter to Arc Members 2025](https://browsercompany.substack.com/p/letter-to-arc-members-2025):_

> ...our metrics were more like a highly specialized professional tool (like a video editor) than a mass-market consumer product, which we aspired to be closer to.

Arc is Logic Pro when they're trying to be GarageBand, or the Premiere when they're trying to be CapCut. And while Logic Pro can get away with charging $200 and Creative Cloud a $50 monthly membership, Arc cannot. This is just not the way that browsers operate. While I would be happy to pay $5 or $10 a month for Arc if it meant continuous support and new features, I doubt that enough people share that sentiment to make it a commercially viable product.

This point was driven home for me when I caught a glimpse of the feature usage statistics that TBC dropped in the same blog post. One out of twenty users regularly make use of spaces? This is insane! I thought that was one of the core features that brought value to Arc! Judging by Arc users' embrace of Zen, an open-source Firefox-based alternative, most are drawn to Arc through a command-driven workflow and a vertical sidebar, maybe bookmarks that look like tabs. That's it. To me, it would be insane for Arc to sink that much time and energy and resources into maintaining a set of two or three features that would be easily adapted by other browsers once the paradigm got popular enough to implement. Then, what would Arc have over its competition, with their mature codebases and deep pockets? Not much.

And this goes back to the fundamental problem with Arc: the program requires users to learn it. While Arc ultimately makes for a better browsing experience, the learning curve associated with it is too steep for a web browser. It's the same reason a text editor like Vim isn't more popular—while its users swear by it, most people don't have the motivation to learn to ride a bike all over again.

I also think this notion of TBC 'abandoning' Arc is flawed in another sense: Arc does not owe you anything! This is a free product that has not once been monetized or attempted to be monetized. You did not pay for this product apart from the time it took you to migrate to it, and even that time is more fun than work. TBC is even spending money to support the AI features in Arc Max. Yet, Arc's users expect TBC to keep adding new features and expand to other operating systems even though Arc makes no money and will never make money.

### Arc's failed experiment

While Arc on MacOS is polished by now, one big, lingering scar remains in the Arc landscape: Arc on Windows. It has been a buggy mess from day one and continues to miss essential feature parity with Arc on MacOS, and with TBC's jump to Dia, it doesn't seem like that will be changing anytime soon. I have made peace with this: Edge is my browser of choice for my job and for the few instances where I run Win10 at home. I get that the Arc rollout on Windows has angered a lot of Arc users, and I absolutely understand that moving Arc into a holding pattern means leaving an unfinished Windows product on the table. But despite this, I do still believe that TBC is making the right decision.

To me, Arc was never meant to be on Windows. It was deliberately built from day 1 as a Swift app instead of a C++ app, which allowed for the rapid prototyping and development needed to make a program like Arc. Electron is the closest cross-platform option that offers the same rapid prototyping, but it is much too slow for a web browser. Apps built with SwiftUI also feel impossibly native—I have always felt that Arc is what Safari could have been if Apple went all-in on its browser.

Although, building Arc in Swift also meant that it had little chance of being ported to other platforms. Swift is about as vendor-locked as an open-source language can be, given that its primary development environment is only available on MacOS. And before Arc was ported, no native UI toolkits were available for Swift on Windows. Despite this, TBC made a valiant effort to port their Swift workflow to Windows, and to a certain extent, they succeeded. It is astonishing that TBC got so far in their development of Arc on Windows given the deck that was stacked against them.

What Windows Arc users need to understand is this: Arc as a product has never been profitable and never will be profitable, and continuing to develop Arc on Windows would be a massive blunder on TBC's part that would do nothing but burn through their VC money. It's a bitter pill to swallow, but it is abundantly clear that a browser will not permeate the market enough to remain viable unless it offers an experience that is both revolutionary and has mass-market appeal. And this revolutionary experience is exactly the unicorn that TBC is chasing with Dia. TBC is much better off as a company pivoting to a new paradigm than sticking with an expensive, sinking ship that did not become as popular or profitable as they hoped.

### So, why Dia?

Users are also angry about the browser TBC pivoted to: Dia. Some Arc users think Dia's AI chat feature can easily be replaced with a browser extension or a quick feature. And I get this sentiment—if you take a cursory glance at the app, its chat window just looks like a standard AI chat activated by a button in the corner. But this ignores how TBC is aiming to take this idea further by integrating AI into the browser itself.

Right now, the crucial thing that AI chatbots lack is context. Sure, these chatbots can view your chat history and look at things you paste into the prompt, but this only works for simple things like summarizing a linked article or rewriting a paragraph. If you want an AI to ingest a long essay you're working on or find a conversation you had a couple days ago or recommend a place to stay in a city based on the activities you've booked, quickly providing enough context to make that work is almost impossible.

For Dia, however, providing this context is as easy as @’ing your opened tabs or your search history, and Dia will automatically ingest whatever it needs to answer your prompt. Instead of the chatbot being stapled onto your browser, it _is_ the browser, which unlocks some pretty cool use cases for AI that go beyond just answering a question.

This, I argue, drives all the value for Dia. Conventional chatbots like ChatGPT can never get this data because a website can't just access the rest of your open tabs or your browsing history for the past week. Chrome wouldn't switch to an AI-based browsing experience because it tears people away from Google. Other browsers with a C++ codebase will take too long to test and ship new features.

Mass-market appeal requires a near nonexistent learning curve and a frictionless onboarding experience, and Arc is unable to provide that with its vertical tabs and command-based workflow. Dia is instead imitating a conventional browser that is interwoven with some more advanced AI features. That seems like a much smarter decision to me than trying to rescue a paradigm that has not demonstrated much mass-market adoption.

This is not to say that Dia will be the pinnacle of agentic AI browsers. Perplexity recently released their Comet browser to pretty positive reception and OpenAI anticipates releasing their own browser soon. TBC is betting that they will offer a UX and UI that is more polished and more intuitive than other companies that don’t specialize in browsers. Whether this will pay off or not is something we will have to see (and prompts a much more welcome debate, in my opinion!) but it is clear to me that this decision is a better one than sitting on a niche tool like Arc.

### The hope for open source

But all of this talk about the end of Arc begs the question: if Arc serves no more purpose to TBC, why not open source it? Why not hand off development to its loyal users that will volunteer their time to further iterate on the product? TBC's official response to this is a bit wishy-washy, but it boils down to this: the _method_ of creating Arc (and Dia) is too valuable to give to the public. TBC believes that they are sitting on a pot of gold with their Arc Development Kit, and by open-sourcing Arc, they are leaking the primary method of building Dia. While I would love to see Arc open-sourced, TBC still needs to keep their value until Dia grows a lot more. And until then, open source is out of the question.

### Next steps

Say you're an Arc user that can't see switching back to Chrome or Firefox or Edge anytime soon. What should you do?

The first option is simple: do nothing! For the time being, Arc will still be getting regular security updates. While no big features will come out, you can keep on using Arc like you have been.

But what if those updates stop coming? The second option is to switch to an Arc competitor. The biggest one right now is Zen, a Firefox-based browser that emulates most of the standard Arc features pretty well. It's in active development, meaning you can still get the dopamine hit of frequent new features, and it's open source, meaning if its creator stops updating the program, its users can pick up the torch.

There is also a third option, and the one I recommend: try out Dia! I was super hesitant of Dia when I tried it out about a month ago, and after getting used to it, I can say that I really appreciate the workflow that Dia is going for. The contextual chat can unlock some awesome things once you train your brain to think AI first and Google second. This, however, assumes that you're not morally opposed to LLMs and you are willing to take TBC's word on data privacy. If those two things aren't dealbreakers for you, give it at least a week's shot, if not more.
