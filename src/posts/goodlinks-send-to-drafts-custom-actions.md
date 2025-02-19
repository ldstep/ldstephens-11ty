---
title: Goodlinks send to Drafts Custom Actions
description:
date: 2023-12-20
tags:
   - posts
layout: layouts/post.njk
---

Posted on December 20, 2023 by Loren

If you use [Goodlinks](https://goodlinks.app/) and [Drafts](https://getdrafts.com/), I hope you're taking advantage of Custom Actions. Custom Actions allow you to create your actions to export and share your saved bookmarks. Additionally, you can trigger URL schemes.

A while back [I wrote](https://medium.com/@ldstephens/how-to-create-custom-actions-in-goodlinks-4dbe4b87c881) the following about Goodlinks:

> I love Goodlinks as my read-it-later app. Even though I love it and think that it's the best reading experience of all read-it-later apps I’ve still been using Instapaper for its Share All Notes feature.

In the latest release, version 1.8.5, Goodlinks introduced support for new custom action tags that are going to let me eliminate the need for Instapaper's Share All Notes: \[selection-html\], \[selection-markdown\], and \[selection-text\] on iOS and iPadOS. These tags will be handy as Goodlinks lacks a built-in highlighting and export highlights feature. Now, I can select text in an article and seamlessly send the selection to Drafts. This is especially handy for creating link posts.

Here are my five most used Goodlinks send to Drafts actions, which include two new actions specifically for selected text:

**Markdown Title, URL – Drafts**

`drafts://create?text={[}[title]{]}{(}[url]{)}`

This action sends the title and URL of the active article to Drafts as markdown.

**Markdown Title, URL, Selection – Drafts**

`drafts://create?text={[}[title]{]}{(}[url]{)}{ }[selection-text]`

This action sends the active article's title, URL, and selected text to Drafts as markdown.

**Selection – Drafts**

`drafts://create?text=[selection-text]`

This action sends the selected text in the active article to Drafts as plain text.

**Title, Author, URL, Selection – Drafts**

`drafts://create?text={# }[title]%0A{*}[author]{*}%0A[url]%0A[selection-text]`

This action sends the title, author, URL, and selected text in the active article to Drafts as plain text.

**Markdown Title, URL, Summary – Drafts**

`drafts://create?text={[}[title]{]}{(}[url]{)}{ }[summary]`

This action sends the title, URL, and summary of the active article to Drafts as markdown.
