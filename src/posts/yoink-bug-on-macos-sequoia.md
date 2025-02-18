---
title: Yoink Bug on macOS Sequoia
description:
date: 2024-10-09
tags:
   - posts
layout: layouts/post.njk
---

Posted on October 9, 2024 by Loren

Hey friends, if you’re using [Yoink](https://eternalstorms.at/yoink/mac/) on macOS Sequoia (15.0/15.0.1), you might have noticed an annoying bug where Yoink stops accepting files. I’ve personally run into this issue, and it’s affecting many users of apps that handle file URLs and rely on security-scoped bookmarks.

The root cause? A macOS bug in the “ScopedBookmarkAgent” process, confirmed by a CoreOS engineer on the Apple Developer Forums. Unfortunately, 3rd-party developers can’t fix this—Apple has to.

The good news: macOS 15.1 is expected to fix the issue, and things should return to normal!

> As a temporary workaround, you can:– Quit Yoink (or any other afflicted app)– Using Activity Monitor.app, quit the ScopedBookmarkAgent process– Relaunch Yoink (or any other afflicted app), and it should work again (for a while)

[Matthias](https://blog.eternalstorms.at/2024/10/09/psa-a-bug-in-macos-15-sequoia-is-causing-issues-in-yoink-transloader-and-other-devs-apps/)
