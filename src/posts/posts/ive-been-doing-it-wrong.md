---
title: I’ve been doing it wrong
description:
date: 2025-01-06
tags:
   - posts
layout: layouts/post.njk
---

Posted on January 6, 2025 by Loren

I’ve been using GitHub all wrong for this site. Instead of working from a cloned repository, I was just using a regular folder of files on my computer. Whenever I wanted to add a new post or make changes, I’d edit them in VS Code, then drag and drop the updated files directly into GitHub’s web interface. I knew this wasn’t the right way to do it, but I didn’t know any better. So, I started searching YouTube for a better way to handle it.

I came across this video [GitHub Tutorial - Beginner’s Training Guide - YouTube](https://www.youtube.com/watch?v=iv8rSLsi1xo) that helped immensely.

What I needed to do was install GitHub Desktop and I needed to clone the repository locally.

Now GitHub Desktop connects GitHub, my local repository, and VS Code together. Here’s how it works:

1. **Connecting to GitHub**: GitHub Desktop links directly to my GitHub account, so I can easily clone repositories and sync my changes with the remote repositories on GitHub.
2. **Managing My Local Repository**: When I clone a repository using GitHub Desktop, it creates a local copy on my computer. This is where I make changes and commit updates.
3. **Using Visual Studio Code (VS Code)**: I’ve set VS Code as my default editor in GitHub Desktop. When I click “Open in Visual Studio Code,” it opens my local repository in VS Code, ready for me to start coding.
4. **Keeping Everything in Sync**:

-  I write and edit my code in **VS Code**.
-  GitHub Desktop tracks the changes I make and lets me commit them.
-  Once I’ve committed, I can push my changes to GitHub or pull updates from the remote repository when needed.

Honestly, taking the time to learn GitHub Desktop has made managing my static site so much easier. I can jump into VS Code to edit, track changes locally, and sync it all with GitHub in just a couple of clicks. It’s been a fucking game-changer.
