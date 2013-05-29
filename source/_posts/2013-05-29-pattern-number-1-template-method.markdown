---
layout: post
title: "Pattern #1: Template Method"
date: 2013-05-29 10:04
comments: true
categories: "Design Patterns"
---

This is one of the simplest design patterns out there. The GoF book has the most concise description of the __Template Method__:

> Define the _skeleton of an algorithm_ in an operation, deferring some steps to subclasses. 
> 
> Template Method lets _subclasses redefine certain steps of an algorithm without changing the algorithms's structure_.

Let's tease apart the description. 

First, notice the use of __subclasses__. This pattern makes use of inheritance heavily. You'll see that it also inherits the good and bad attributes of inheritance (pun intended).

###Define the _skeleton of an algorithm_ in an operation, deferring some steps to subclasses

This is where the 'Template' bit comes from. Let's see some code:

{% codeblock lang:ruby %}
puts "Hi Guys"
{% endcodeblock %}