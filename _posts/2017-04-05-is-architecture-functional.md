---
layout: post
section-type: post
title: Is architecture functional?
date: '2017-04-05T14:47:25+02:00'
author: Jørn Ølmheim
category: tech
tags: [ 'software architecture', 'functional architecture' ]
---
Functional architecture? What do you mean? Of course the architecture works, that's the whole point...

No, what I mean is is architecture influenced by the ideas and principles behind functional programming. Specifically:
 * Pure function (side-effect free)
 * Composability
 * Idempotency
 * Immutability

I am convinced that software architects are mainly function oriented when they build their software architecture, and again I'm talking about the functional principles rather than the functionality of the system. Why? Because we are mainly thinking about system components, sub-systems and sub-sub-systems and how these are composed. We focus on interfaces and the messages flowing between the systems. This is mainly a functional endeavor where we think about components mainly as pure functions, and how they can be composed into a working whole.

Now what about the Quality Attributes? After all the quality attributes are orthogonal to the functionality of the system, right? There is no denying that focusing on functional concepts like the ones listed above will lead to a certain set of system qualities, and they will end up pushing the quality attributes in a certain way. As far as I can tell, driving the architecture with these concepts will lead to a highly modular, distributed and scalable system, so does that mean that functional architecture is only suitable for certain types of systems? That may be something to consider for a future article.

So what should we call such a thing? I conclude that "Functional architecture" is the best we can do for now. I did consider "Function-oriented architecture" for a hot minute, but decided that it was neither more precise or more descriptive.

I think we will see more work on this concept in the years to come, as the so called "Internet-scale" applications start to be what everyone have to do.
