---
title: Project size/complexity/cost estimations & Agile hype (part 2)
layout: post
author: Rafal Maciag
tags: [Agile, EventStorming, EventModeling, DDD]
---
![abstractions]({{site.baseurl}}/img/abstractions.jpg)

- Faraon: Hey, how much would it take to build one piramid??
- Architect: I don't know. Maybe 15 years...

(After 15 years)

- Faraon: Hey, how much would take time to build one more like that???
- Architect: Same!!!

## If it was a Product Owner and a Developer, then he'd answer the second question: Ohh now it's easy - half a year! :-)

Why we fail here:

1. Because we don't know how to make implementation process repetable.
2. Because requirements might not have everything that is required for developer to make it repetable.

So what indeed does a developer?

* Figures out missing requirements? (sometimes)
* Figures out how to design right **abstractions!**

# How to find right abstraction?

The answer to the question was already pointed out in previous article. We need to understand the domain with all required abstraction that need to be modeled. In order to explore the domain we can use #EventStorming. If we have explored most of the possible requirements, then we can model/design with #EventModeling. This will make everybody on the same page and involve in design process:

1. We'll have **mockups** - so that people can visualize what can be there on a page
2. We'll have **events/facts** - that will tell you a story, that is selectively observed with the right business meaning.
3. We'll have **conclusions/read-models/implications** - that naturally construct beliefs with assumptions and then proceed to actions.
4. We'll have **given/when/then** statments that will allow you to elaborate on the above and conditions in the flow and state for live documention.

<a href="{{site.baseurl}}/img/blueprint_large.jpg">
![Event Modeling by Adam Dymitruk]({{site.baseurl}}/img/blueprint.jpg)
_Source: eventmodeling.org by Adam Dymitruk_
</a>

# We will have a decent description on right level of detail that create natural abstractions.

This service-blue print is also on the right level of detail to calculate project size/complexity. Before we do it, let's find out **How implementation from this service blue-print can be so repetitive**?  

For those familiar with DDD, the answer would be: _If you know the detailed DDD model, the implentation is straight-forward._ Some might argue that DDD is not required here, I agree, but I'll leave this for next articles :)

If you are not familiar with DDD, next paragraph is for you :)

_I won't cover DDD here though :) Instead I'll focus on the concept. There is no magic in IT systems. They proces information. How they do it, can be described with natural language. If you are very carefull with the descriptions, we might explain every implementation detail. It's just like reading an equesion. The art of writing a poem in natural english that can then translated 1-1 to source code and vice-vera is the art of DDD. So what does it mean?_

When someone tells:

## There's a purchase order submited [event/fact] in the system, and it is relevant.

With DDD/BDD implementation patterns of your choice, you will be told exactly what files/classes/source-code this natural statement caused to create. They will derive every name (of class, method or even a variable) from the very sentences you used. There isn't (shoudn't be) anything more in the code that is hidden from the reader.

## Therefor if you know how to describe the (business) story in language formulated within right abstractions, the development process is repeatable.

In next articles You will read about:
* How can we estimate size of information systems? Is it possible?