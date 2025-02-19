---
title: Keyboard Maestro Macro - Close all open tabs and hide Safari
description:
date: 2023-11-20
tags:
   - posts
layout: layouts/post.njk
---

Posted on November 20, 2023 by Loren

During the research phase for blog posts, I often end up with numerous tabs open in Safari. Once I've finished utilizing these tabs, I'd like to have the option to close them all and hide Safari simultaneously.

There are a few different ways to close tabs on a Mac. The simplest way is to use the keyboard shortcut Command+W. Alternatively, you can click on the “x” button in the top-left corner of each tab, or you can right-click on the tab and select an option from the menu.

![](https://miro.medium.com/v2/format:webp/1*y1ITbicOumgT4Xlz8hqEfQ.png)

If you want to close all tabs in a window, you can use the keyboard shortcut Command+Option+W. Whatever option you use to close the tabs, Safari is still the active window, and you still have to hide Safari Command+H.

As I mentioned above, I want all this to happen simultaneously with a keyboard shortcut, so I created the following [Keyboard Maestro](https://www.keyboardmaestro.com/main/) macro.

Safari Group![](https://miro.medium.com/v2/format:webp/1*tVrNmNMZGLvwJ4k3DCBcHw.png)

Macro![](https://miro.medium.com/v2/format:webp/1*JV1qar75Ibma9b9J1AaYXw.png)

Now when I execute the Option+Command+H keyboard shortcut in Safari, it closes all the open tabs and hides Safari. This saves numerous clicks and keystrokes.
