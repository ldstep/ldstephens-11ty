---
title: GoodLinks to iA Writer Custom Actions
description:
date: 2024-06-17
tags:
   - posts
layout: layouts/post.njk
---

Posted on June 17, 2024 by Loren

Hey friends, as I mentioned the other day, I’m switching to [iA Writer](https://ia.net/writer)for my blogging and writing. This means capturing my ideas directly in iA Writer. Since [GoodLinks](https://goodlinks.app/) is my go-to read-it-later app, I’ve created some Custom Actions that seamlessly transfer content from GoodLinks to iA Writer.

Previously, I wrote about [creating Custom Actions](https://ldstephens.me/how-to-create-custom-actions-in-goodlinks) in GoodLinks and it included actions for sending content to Drafts. I’m excited to share three Custom Actions for sending content from GoodLinks to iA Writer with you.

**Title, Author, URL, Selection to iA**

`ia-writer://x-callback-url/new?text=[title]%0A{_}[author]{_}%0A[url]%0A[selection-text]`

This action sends the title, author, URL, and selected text in the active article to iA Writer as plain text.

**Selection - iA**

`ia-writer://x-callback-url/new?text=[selection-text]`

This action sends the selected text in the active article to iA Writer as plain text.

**Markdown Title, URL - iA**

`ia-writer://x-callback-url/new?text={[}[title]{]}{(}[url]{)}`

This action sends the title and URL of the active article to iA Writer as markdown.
