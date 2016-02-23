---
layout: post
title:  "Complaining ≠ localization: Why localizers and developers misunderstand each other"
description: test
---

I've been to a localization conference or two over the years. One thing that struck me as odd was how much of it was centered around moaning about how hard it is to get your devs to not concatenate their strings, provide context in the form of code comments, basically writing localization-friendly code. At first it was vaguely annoying and then interesting how common it was across companies and then it became kind of endearing. There are a few reasons as to why this is.

####Localizers and developers don't speak the same language

This can be largely literal since the localization industry is full of people who come to it from a linguistic background--most of them from other countries. But when a large portion of your localization team is comprised of translators and linguists, it makes sense that there would be a bit of a disconnect when you put them to work in a software development environment. This disconnect is further exacerbated when you say things like "speak developer", and tell your localization colleagues that developers don't care about localization. You create an "us vs. them" mentality that is rarely productive and only divides your development and localization team further. This only serves to increase the mystery of localization and is detrimental to your agenda.


####We all want to create an awesome international product. We're just bad at giving developers the tools they need to do that

The common ground is this: we all want to do right by our users, international and otherwise. I've yet to meet a developer or product owner who didn't feel a responsibility to create a usable product that meets the needs of the user. If you don't work for a company where this is a value, you may want to shop around for a new job. But basically, if you want a developer to be on your side, all you have to do is approach a localization issue with a "let's fix this together" mentality. The problem is, localizers fall prey to major impostor syndrome and have a hard time having that mentality when they honestly don't think they can offer any good, technical advise. Because of this insecurity, we often just throw our problems over the fence and say "fix it" trusting that the all-knowing developer will have the answer without doing any research (this is rarely the case and I'll explain why in a future post). But the reason for most of your developer woes is this

####Localizers are problem finders, not problem solvers

Let's explore a typical localization bug. Localization testing happens late in the development cycle as always and the development teams have likely already moved on to working on the next release. During testing you find an issue with the Japanese translation caused by concatenation, you file a bug against the dev (who can barely remember the code he wrote yesterday, let alone last month) saying that he should have known better and should fix it ASAP. This is in addition to more important work he is doing for the next release and this sounds like a low priority bug. And honestly, it is low priority except that Japanese users aren't very forgiving when it comes to typos and generally incorrect UI. You've seen hundreds of bugs like this before and are pretty fed up at this point so you write the dev a long-winded email detailing the intricacies of the Japanese market and generally complaining how coding mistakes like this are going to cause you to lose Japanese users. None of this is very motivating. It’s because you’re posing a problem instead of proposing a solution. We’ve all worked with people like this—the ones that spend their energy complaining about problems instead of thinking of solutions. They aren’t very much fun to work with.

And that is largely due to the fact that localizers feel like second-class citizens in the software development world. Overcoming imposter syndrome will be covered in a future post. In the meantime, let’s focus on solutions instead of problems.

