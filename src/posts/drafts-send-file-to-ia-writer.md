---
title: Drafts send file to iA Writer
description:
date: 2024-04-08
tags:
   - posts
layout: layouts/post.njk
---

Posted on April 8, 2024 by Loren

[Drafts](https://getdrafts.com/) is my go-to app for capturing all my text-based ideas. Once I'm ready to turn those ideas into blog posts, I rely on Drafts actions to move them to [iA Writer](https://ia.net/writer), my preferred writing environment.

Previously, I used a “Save files as” Drafts action, which involved a few cumbersome steps. First, I had to manually change the file extension from .txt to .md (Markdown format for blog posts). Then, I needed to navigate through Finder and select the specific folder (Ideas or Drafts) where I wanted to save the file. This process felt inefficient, and I wanted a more streamlined way to move my content directly to the target folder.

To create an action to do exactly this requires using Drafts [Bookmark](https://docs.getdrafts.com/docs/settings/bookmarks)feature.

> A bookmark is a reference to a folder in the file system. Bookmarks allow you to grant permissions to work with files in folders that Drafts would not otherwise be able to access due to App Sandboxing security.”
>
> The [File action step](https://docs.getdrafts.com/docs/actions/steps/services#file) can be used to save content from Drafts to files. File action steps can be configured to use a Bookmark by selecting the “Bookmark” destination, and assigning a bookmark name.

To get started, I installed the “Save to File in ‘Test’ Bookmark” action, which writes to a file named “Test” in a designated bookmark. I then customized the action for my needs, creating Bookmarks for both my Ideas and Drafts folders in Finder. With these actions in place, I can now save directly from Drafts to the desired folders. Since iA Writer mirrors these folder structures, the files automatically appear in the corresponding locations within iA Writer.

![](https://i.snap.as/S21laMj7.png)

Resources:

1. [Bookmarks | Drafts User Guide](https://docs.getdrafts.com/docs/settings/bookmarks)
2. [Save to File in “Test” Bookmark | Drafts Directory](https://actions.getdrafts.com/a/1ps)
