---
title: When "Check Spelling While Typing" breaks on Mac, do this to fix it
description:
date: 2024-08-04
tags:
   - posts
layout: layouts/post.njk
---

Posted on August 4, 2024 by Loren

Yesterday, while doing some writing on my MacBook Air, I realized "Check Spelling While Typing" wasn't working. I have no idea why it had stopped working. What the fuck? I guess it's one of the those things that just happen on a Mac occasionally. Anyway if this ever happens to you here's how to fix it.

-  Open Terminal and copy and paste the following:
-  `defaults write -g NSAllowContinuousSpellChecking -bool true`
-  Restart the affected apps (or your whole computer)
