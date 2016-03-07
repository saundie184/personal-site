---
title: Tips to help you debug
author: Saundie Weiss
date: 2016-03-05
template: article.jade
---

I've been coding now for almost six months, and I love it! Something I learned very quickly was that debugging is an essential part of development.

<span class="more"></span>

I often find myself in cycles of highs and lows. I can go from doing something incredible and being so proud of myself to breaking everything and watching my program crash. Then, I bang my head against the wall for a while. Eventually I solve the problem and begin to feel like I am on top of the world again!

My boyfriend has seen me go through this cycle many times, so I've decided to write down a couple questions that he can ask me when I'm stuck. Next time I'm banging my head against a wall, he can use this nifty list to help me trouble shoot.

1. Are you looking at the right files?

While this may sound simple, I can't tell you how often I'm expecting something to work on the wrong file or I'm looking at the wrong port. I also need to check to make sure my files are in the correct directories and the paths are set properly.

2. Have you required everything that you are using?

A lot of times I have the correct code, but I don't have the proper dependencies required. I've also caught myself requiring things in the wrong order so they overwrite each other or don't load properly. Checking to make sure all the right dependencies (and the correct versions) definitely makes a difference in whether or not my code works.

3. Are you using all the tools in the Inspector that you could be?

By this point, this should be a no-brainer for me, but as with a lot things we do often, we some times forget the basics. Using Chrome Inspector Tools is super powerful. I don't know how to program without them.

4. Have you done any console logs?

The answer to this one should be, "Yes, but I can do more". Breaking down problems into smaller ones is how you solve the larger problems. In JavaScript, console logs can help you pinpoint where your code is not doing what you think it should. I've learned to integrate these into my normal practices, but it's always a helpful reminder to do more!
