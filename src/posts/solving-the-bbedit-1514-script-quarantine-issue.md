---
title: Solving the BBEdit 15.1.4 Script Quarantine Issue
description:
date: 2025-02-23T09:57:48Z
tags:
   - posts
layout: layouts/post.njk
---

Posted on February 23, 2025 by Loren

Hey friends, if you're like me and use BBEdit, you might've run into a weird error after the 15.1.4 update. Basically, your scripts suddenly stop working, and you get this message: 'This script file has been quarantined by macOS (application error code: 13312)'. Super annoying. I reached out to BBEdit support, and they gave me the fix. I'm sharing it here so you don't have to pull your hair out!

> Made a change so that AppleScript execution, whether implicit (as in Startup Items or text factories) or explicit (via the Script menu or other UI invocation) will fail if the script file has been quarantined by macOS.
>
> The OS will generally quarantine files that have been downloaded, but may do so for other reasons; there are various tools for correcting this, but the most straightforward is probably the `xattr` command line tool.
>
> The following Terminal command will remove quarantine from any given file (use the actual File path rather than "/path/to/file"):
>
> xattr -d com.apple.quarantine /path/to/file

This was in the release notes, but who reads the release notes. Obviously not me.
