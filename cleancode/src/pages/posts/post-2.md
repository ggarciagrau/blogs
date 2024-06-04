---
layout: ../../layouts/MarkdownPostLayout.astro
title: 'Intention-revealing names'
pubDate: 2024-06-04
description: 'Naming concept'
author: 'Gerard GG'
tags: ["meaningful-names"]
---
Choosing names that reveal intent primordial. It sound obvious because it is. But what happens when you revise a code you wrote few days ago? You probably have trouble determining what exactly a component, function or even variable name means or comprises. Choosing names, apart from being obvious is hard.

A name should be capable to answering all the questions that come to your mind as much as possible of course. Code comments are by no means an excuse to compensate poorly chosen.

I consider a bit pointless to write a few examples and how to correct them, if one does not have comprehension problems, one realizes almost immediately that something is not understanble at all. Another thing is that we end up goofing off and prefer other more straightforward tasks. 

In turn, I'm going to provide a few personal guidelines I usually use when I hesitate about choosing some names:
- Don't hesitate to use long names if necessary.
- Be as specific as possible.
- Don't use useless boilerplate words (for example list or array as a suffix).
- Don't use magic (hardcoded) values.
- Prefix boolean variables with `is`.