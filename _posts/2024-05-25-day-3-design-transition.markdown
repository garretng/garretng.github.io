---
layout: post
title:  "Day 3 - Design Transition"
date:   2024-05-26 09:57:59 -0700
categories: Coding
---

Just woke up and I'm looking over my code trying to figure out where I left off. I should have marked down some notes last night but I basically passed out in my chair. Here's a what I'm looking at:

![start of day 3 snapshot](/images/day3-game-snapshot.png)

Very simple but along the top of the screen we have a key stat trackers which includes stored power, stored bitcoin, the game timer and the current threat level the player is facing.

In the center we have our main generator as well as our bitcoin toggle button.

I just implemented the mechanic that modifies the timer's count-down speed based on the current threat level. The threat level increases every six(6) seconds by a random number between 1 and 5. This inturn increases the speed at which the game time decays.

I'm now deciding what feature to work on next.
