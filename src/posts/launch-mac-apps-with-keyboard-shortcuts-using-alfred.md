---
title: Launch Mac apps with keyboard shortcuts using Alfred
description:
date: 2022-02-25
tags:
   - posts
layout: layouts/post.njk
---

_25 Feb, 2022_

Yesterday, [I wrote](https://ldstephens.me/launch-mac-apps-with-keyboard-shortcuts-keyboard-maestro) about launching Mac apps with keyboard shortcuts using [Keyboard Maestro](https://www.keyboardmaestro.com/main/). If you’re an [Alfred](https://www.alfredapp.com/) user, you can do the same thing with an Alfred workflow.

As an example, here’s my workflow to launch Safari with the hotkey ⌥S. You’ll need the [PowerPack](https://www.alfredapp.com/powerpack/) to do this.

Step one is to create a new blank workflow.

![](https://i.snap.as/jAeGdksC.png)

Step two is to set up a hotkey trigger.

![](https://i.snap.as/8IjBw1sU.png)

Step three is adding the Launch Apps action and dragging in the application(s) you want to open. The easiest way to do this is to search for the application or file in Alfred and drag it directly from Alfred's results into the action box.

![](https://i.snap.as/qdTFSCgb.png)

![](https://i.snap.as/yCyio0EF.png)

Optionally, check the "Toggle visibility for apps" to tell Alfred to show and hide the app. Connect the action to the hotkey to quickly launch the app.

Using keyboard shortcuts lets you perform actions faster and more efficiently, cutting down on mouse and trackpad usage.

In the next day or two, I’ll show you how to do this in [Raycast](https://www.raycast.com/). It’s super simple. So download it today and in a couple of days, you’ll be launching apps with keyboard shortcuts. Remember it’s FREE.
