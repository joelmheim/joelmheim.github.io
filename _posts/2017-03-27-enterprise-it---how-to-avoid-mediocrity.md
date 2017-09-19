---
layout: post
section-type: post
title: Enterprise IT - How to avoid mediocrity
date: '2017-03-27T11:06:46+02:00'
author: Jørn Ølmheim
category: tech
tags: [ 'enterprise it', 'learning', 'agile', 'software architecture' ]
---

Let's talk about Enterprise IT.

Enterprise IT must die in order for IT in the enterprise to provide value to the business. Why?

Well let's talk about Enterprise IT...

A good colleague of mine once asked a very pertinent question:
>"Why is it that we (the big Enterprise) with all our resources and people, hardware and competence, are not able to outperform the small start-ups that only have a handful of developers?"

If you think about it, this is a very good question. And there are of course many contributing factors. You can point to bureaucracy, for instance. Is it me or is the ending of that word dangerously close to crazy? Coordination is another that is difficult in large organizations. But what I want to spend time on today, and as I'm sure you have gleaned if you have seen the title of this talk, is mediocrity. As a little disclaimer, I want to say that I'm talking more about mediocre effort than mediocre ability. There is a difference.

Enterprises attract and cultivate mediocrity. How does this happen?

Let me tell you a story:

>Once upon a time (all stories start like this, right?)... Once upon a time, there was a software developer working in a big company. He had heard that the company had a very particular and pressing business need, and he set out to implement a solution. He started out small, as solutions do, but our hero quickly saw that he would need some help, so in order to get the work done he recruited a few other developers to help out with building the solution. Having built a great application that solved the initial need, the business quickly found out that they had other more or less related needs that could be solved in the same way. Over the years the solution grew and became a point of pride for the business, and our hero and the team with it. So the years went, and technology changed, and some of the team wanted to change with the times. The problem was that our hero wanted to keep the core of the solution that he had created and saw as the key value of the solution. Let them change around us, he said, and so while the solution changed around him, he kept the core the same, only adding new data and changing as little as possible. This lead to a situation where many good developers who joined the team were disillusioned over time and left, while our hero thrived on his exceedingly rare knowledge of the core solution. This combined with the corporate governance dictating the technology in other parts of the solution (which by the way had been decided by Corporate IT in an attempt to modernize the technology platform), and the ever increasing demands from the business to solve new needs, lead to a development team that stopped paying attention to the advances in the outside world, and contented themselves in building an ever more crooked tower on their core base.

As we can see the team finds itself in a hole that has been dug partly by the business, partly by corporate IT and partly by our hero. All of them with the best of intentions. The team has become reactive to both the business needs and the technology development instead of proactive and this has lead to both production and delivery problems due to a complex and unmaintainable solution.

This in an of it self is bad enough, but seen in the context of the current movement within large enterprises it is even worse. I'm guessing you've all heard about Digitalization. This is the current buzz-word in many IT organizations. And even if most of us don't exactly know what it means, (you may think you do, but you really don't). What we do know is that it puts increased pressure on the IT function to not only support, but to start driving the business. In order to do this we need flexible solutions, and the best developers we can get. Mediocrity in effort or ability is no longer something we can tolerate.

In a series of [articles](http://www.daedtech.com/how-developers-stop-learning-rise-of-the-expert-beginner/), Erik Dietrich, writes about a dead-end in the Dreyfus model he calls the Expert Beginner. This state happens when you as an Advanced Beginner start to think that you know all you need to know and start amassing many years of experience with just the same type of technology and never moving forward. This is the Dunning Kruger effect in practice, the less you know the more you think you know. This state is actually cultivated by central decisions and mandated technology use. And having situations like in our story where some developers are exalted by the business and elevated to a senior position without having a broad enough competence combined with central decisions, however well intentioned, leads to the best developers finding other projects or worst case leaving the company. This is what leads large companies to mediocrity.

So let's turn to how we can avoid this. There are multiple factors to deal with. Let's start with the people dimension.

In his [animated talk](https://www.youtube.com/watch?v=u6XAPnuFjJc) at the RSA, and best selling book [Drive](http://www.danpink.com/books/drive/), Dan Pink tells us that people are primarily motivated by three factors: Autonomy, Mastery and Purpose. This means that having other people either within the team or outside the team dictating what you can do will decrease motivation. We should really let the talent, competence and drive of the individual rather than position in the organization dictate who makes the technology choices. This will lead to increased motivation and a higher likelihood that our employees will take charge of their own development.

The counterargument to this is always the notion that we as an enterprise need a finite set of technologies to deal with, otherwise we'll be overwhelmed. And there is some truth to this. The problem in most enterprises is that a choice of a new technology seldom if not never leads to the replacement of an existing one. It is very hard for some reason to move the entire enterprise in a new direction based on one groups discoveries. So, thinking that making a technology choice is the end-all be-all that will solve all problems, is in my opinion a fallacy. Especially if this choice is made by a central governing body rather than the talent on the ground.

The key to driving innovation and avoiding mediocrity in your IT business is to allow diversity, create a forward-looking software innovation group and make sure that solutions from this group trickles into the rest of the IT organization. This applies to the methodologies and tools used by this group as well. Perhaps the most important part of this is establishing and maintaining this bridge between the innovation group and the operational organization. Without that you will just increase the gap for the best programmers and give them an incentive to leave, and the motivation for the rest of the group will be lowered as well.

In large organizations this does not have to be a single group, so any technology innovation can be done in such groups so long as this bridge back to the operational part of the organization is in place. It is also important that the groups are aligned, and that decision making and governing bodies such as corporate IT take their cues from these innovative groups. This is the key to any successful R&D organization as well as any enterprise IT organization, and unfortunately often is not implemented well.

The other important part is to evolve the existing portfolio as new technology, methods and tools are discovered. Getting the rest of the organization to adopt these innovations is tricky enough, let alone having such adoption lead to the phasing out of old technical debt. So if we don't have some architectural oversight we will end up with this (image), when what we really want is something like this (image).

Creating a group with the clear responsibility of mapping and guiding the IT architecture for the whole enterprise is key. This group can help the enterprise identify the good and bad examples of software architecture that exists and help make sure that new solutions and the whole portfolio evolves in a more planned way.

In summary:
 * Architectural oversight is important in the enterprise, but you should govern by architecture principles and instantiated architecture patterns to guide the development of the individual components of your systems as well as the interactions between them.
 * Technology choices at all levels should be done by the development teams. A good model for this is to have a largely independent "Software Innovation" group or groups, that is responsible for keeping an eye on the latest developments, try them out by building innovative solutions to business problems, and bring solutions, methodologies and tools into the rest organization.
 * The key here is to get the bridge between innovation and operation in place so that new ways of working, new tools, and new technology trickles down into the entire IT group.
