---
layout: essay
type: essay
title: The first weeks of Javascript
date: 2016-09-01
labels:
  - Software Engineering
  - Learning
---

In the first weeks of my course on Software Engineering, I've also been exposed to Javascript for the first time. Using the athletic software engineering model (http://courses.ics.hawaii.edu/ReviewICS314/morea/introduction/reading-athletic-software-engineering.html), we have started on a fast, but above-all consistent, pace. Learning in this way has, so far, kept me focused on the next step - there are observations about the language that I've picked up along the way, but I haven't had a chance before now to dive in, and speculate as to what they might mean.

## On language and appearances

So far, I'm well versed in Java and C, and I've just touched on Lisp in the same week I started learning Javascript. Lisp, as a prefix language with drastically different syntax, stands out starkly from the other three languages - at least at first glance. But I would say that while Lisp may look very different, Javascript feels very different from the two I'm most familiar with.

The very first thing I noticed was the lack of variable types, at least of the sort I'm used to. When I was first learning Java, I was taught that among its defining characteristics, Java was a 'highly typed' language, before I had any context to which I could attach that distinction. From the very first lesson in Javascript, this was clearly not so. Numbers were a var. Strings were a var. Then, I found, even arrays were a var! "I simply do not care about that," the array-of-vars-stored-as-a-var seemed to say.

If this says anything about the design philosophy of the language, I would hazard that Javascript strives to be flexible. Indeed, in just about every micro-lesson, I've learned that an element of Javascript syntax is about the same as Java or C, or that it strives to be simpler: straightforward, and as flexible as possible. 

To give one example, I was recently trying to recall the syntax to concatenate strings. Is it ".concat"? All spelled out, ".concatenate"? I was about to turn to Google when I asked myself, "what is the simplest way I could express that idea?" And of course, my answer produced working code: "+=".

## On data and simplicity

But, stiving to be something, and being that thing, are not one and the same. One of several distinctions between Java and C is how the languages store data. C allows storage on the stack or on the heap, and it allows objects and variables to be in either place. In Java, objects go on the heap, simple variable types belong on the stack. That way it's simpler - after all, the programmer doesn't really need to know what's going on behind the scenes, right?

Until it actually makes a difference, which it is bound to do. And then you have a wrapper class, an inelegant workaround. Even worse for the new programmer who learns about classes and objects, variables and wrapper classes, all without really addressing the underlying workings that bring about such distinctions. I for one - and I suspect I'm not alone - had to learn C before I really knew what I was doing in Java.

But to return to Javascript, I was saying the very first micro-lesson introduced var, and it all seemed so simple. Enter "const," enter "let." The reason to use "const" seems clear and practical. But for "let," so far, all I know is that "var" doesn't work quite the way it's supposed to, for reasons I hope to learn.

I remain hopeful Javascript will prove to be as flexible, and as simple and straightforward as it first seems. And I have reason to be optimistic, in that experiencing other languages might provide the insight that I need to avoid false assumptions that lead to problems you don't know how to approach. That I have enough context to make good use of what flexibility and simplicity is there, even when simplicity and flexibility seem so often to be at odds with one another. But I am wary as to what might lie behind the curtain.




