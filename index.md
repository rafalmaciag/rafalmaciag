---
title: Project size/complexity/cost estimations & Agile hype (part 1)
layout: post
author: Rafał Maciag
date: 2019-09-08
tags: #Agile #EventStorming #EventModeling #DDD
---
![evolution](img/r-evolution.jpg)

**Project size estimations** and then execution, are the burden for every Product Owner and Project Manager. Business always wanted to know:

* How much project will cost?
* When the project will end?
* How much this/that feature costs/takes time?

Practical agile principles should empower the **Business** to:

* Check out new hypothesis and decide, based on data, which is better. [[DataDriven](https://www.springboard.com/blog/data-driven-design/) / [LeanStartup](http://theleanstartup.com/principles)]
* Decide on pipeline's/work's velocity - scale easily work approximately proportionally to size.
* Demand that feature unit cost doesn't increase with feature set.
* Change easily the delivery order of features, without affecting project costs.

However agile itself or/with microservices-hype seems not to fulfill entirely any above of demands. The main reason is that:

They do not take under consideration combined *costs estimation, requirements gathering with repeatable method of implementation (with right design) and delivery*.

It feels we should know by now how to process information.

It's also said that you cannot precisely calculate project size/complexity and there isn't anything like a cost per functional unit. We failed to define the unit - some attempts:

* [Function Point Estimation](https://en.wikipedia.org/wiki/Function_point)
* [Use Case Points [UML based]](https://en.wikipedia.org/wiki/Use_Case_Points)

Those ways of estimation do not tell you (your team) how you should implement requirements nor how to naturally make sure Business understands what was ordered. And so Teams fail because there is too much uncertainty and we cannot construct a strict schedule.

On the other side, in **Agile**, user-stories (features) should be [estimated relatively with story-points](https://www.mountaingoatsoftware.com/agile/planning-poker), where the measuring base unit is defined by the team. Then you cannot easily compare velocities from different teams/companies/on the market. Also you cannot estimate the whole project, only the next iteration. You may allocate resources for cetain time and periodicly check velocity of the Team.

In software-house's practice however, a min/max estimation is usually done - you might argue that it is not Agile then - fine. Very rarely a buget is allocated for the Team (Time), that **is believed** to work in such a [complex](https://en.wikipedia.org/wiki/Cynefin_framework) environment that is paid just to find a way through.

If the budget is allocated, then the only way to adjust is to change the scope (feature-set).
So, Business has **no guarantee** that certain feature-set will be completed within the **budget**. (Because, indeed feature-set hadn't been defined)

__I dare to say, we've been wrong.__

## The new era of information processing will relay on **understanding how people think and store/share their knowledge.**

[#EventStorming](https://www.eventstorming.com/), [#StoryTelling](https://domainstorytelling.org/), [#DDD](https://en.wikipedia.org/wiki/Domain-driven_design) and [#EventModeling](https://eventmodeling.org/posts/what-is-event-modeling/) are next chapters for natural information systems' modeling evolution.

In next articles You will read about:

* Waterfall and Agile, how human's thinking, natural communication and knoledge play their roles in those methodologies?
* Why we need something more than just "Agile", what there is to demand?
* How can we estimate size of information systems? Is it possible?
