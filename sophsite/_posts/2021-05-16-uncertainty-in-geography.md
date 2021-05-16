---
layout: post
title:  "Uncertainty in Geography"
date:   2021-05-16 15:39
categories: misc
---
'Geography is not a real science' - we've all heard this before in some form. 

I have personally heard it many times from friends and parents, and care less every time. Geography's place in science won't be discussed today, but the validity of geography as a scientific discipline will always come into question when discussing uncertainty. I love uncertainty almost as much as I love complexity. They are both really interesting, fine-grained problems to think about. Unfortunately, the more I think about uncertainty when it comes to geography, the more I question choosing to dedicate what will probably be my entire working life to it.

So, what am I talking about here? I am not entirely sure. This blog post is mostly just to test whether my web server works. Might as well talk about something rather than a boring `\lipsum`. Basically, geography is important and useful, but here a couple of things that I have hated that contribute to my general feeling of uncertainty towards the subject.

#### Rocks
We all had rock collections in high school, right? On the off chance that you aren't as cool as I was, all you need to know is that rock testing matters. The hardness, mineral composition, specific gravity and so on are all important measures that we need to assess. In the field, this can be difficult, as you can't lug an electron microscope up even the most thoroughly board-walked DOC track. And so, we still commonly use something called the Schmidt Hammer. These can fit in a backpack, and work by measuring the rebound of a spring to test mineral compressive strength. Great compromises are made so that we can test in the field, and the problem is that Schmidt results are used in the real-world. Local sample variation, local gravitational force, water content and so much more affect the rating. So much so that upwards of ten samples need to be made across the same rock. My problem is that nothing here is absolute. It will never be perfect, and no two samples (even of the same mineral) will be the same. What's even worse is that geologists STILL use their rock hammers instead of metric scales in photos of outcrops etc. They think it's good enough to place their hammer on top of a rock instead of having even a ruler to show scale... Obviously I am basing my claims off of a stage II earth sciences course, so I am almost definitely wrong, but we really should have moved past even teaching these methods.

#### Maps
[It's really easy to bash Shapefiles](http://switchfromshapefile.org/#shapefileisbad). They suck, and I avoid them as often I can - which is not very often, they are ubiquitous as good old `EPSG:4326`. I am still yet to be convinced that a `.csv` can't do everything that all proposed competitors can, but I must be wrong, so please let me know why. While we are on maps, I might as well also say that 'mapping conventions' are pretty outdated. I am still a big proponent of two-dimensional maps for decision-making, but insisting on North arrows plastered on all of them at a low level is pretty ridiculous to me. Assume North, label all else is my rule of thumb.

#### High-Level Software
Some of the GIS software that is used is notoriously convoluted. I can't tell you how many times I have told students to 'turn it off and on again' when their mapping escapades fail (we all know what software I am talking about here). This is the only part of this rant I actually have a decent bit of experience in, so I will break it down:

- Black box errors: Desktop GIS software has terrible error messages. Those that are wonderfully closed-source don't even have gritty logs to pour over if need be. This makes it extremely difficult to diagnose anything.
- Inconsistency of output: There is always a margin of error for answers to lab questions in GISCI. These are numeric answers, but still need a margin of error because of the inconsistency of geogrocessing. Maybe we aren't controlling some extremely specific environment setting or something, but how would we ever know? 
- No accounting for edge cases: If you know me at all, you will know that I loathe spaces in file names. But this is not something that should cause a program to crash. It is as basic as a syntax change to fix these things, and common desktop GISystems still cannot handle it. Got forbid you have a space in your file name, our source doesn't account for such an unlikely event (see: My Documents).

Luckily, once you get far enough into GIS you can learn to rarely touch desktop software and can do everything in code. The problem with this is that most analysts can't do this, and so (at least in my mind) there is a significant amount of uncertainty in maps used for decision-making.


#### You Made It
...through this waste of bits. I don't think this will contribute to the greater knowledge of the human race or anything, but the markdown seemed to work, so that's nice. Plus, it does feel good to have my thoughts on the uncertainty in GIS software, at least, on record. And my hatred for shapefiles. In any case, have a good day.