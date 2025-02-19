---
title: Apple Private Relay - It's not worth the Wi-Fi speed sacrifice
description:
date: 2023-10-26
tags:
   - posts
layout: layouts/post.njk
---

Posted on October 26, 2023 by Loren

A few days ago, I experienced an unexpected Wi-Fi slowdown, so I an investigation. We have Gigabit internet, and our Wi-Fi typically delivers speeds between 750 Mbps and 1000 Mbps. To start, I ran a speed test on my Eero router and received 998 Mbps. That indicated that the issue was between the router and my devices. Next, I conducted speed tests on my MacBook and iPhone, but they were achieving speeds between 150 Mbps and 250 Mbps. I was left wondering, what the fuck could be causing this?

After some fiddling, I recalled that a few weeks ago, I had enabled Apple Private Relay. It immediately struck me that this might be the culprit. So, I disabled it on all my devices. An not to my surprise, my Wi-Fi speeds returned to normal across all devices.

Private Relay is a network security feature provided by Apple to its iCloud subscribers. It serves as an iCloud security feature that safeguards your internet browsing history by routing your data through two separate internet relays and encrypting your DNS records.

While I do recognize the value of Apple Private Relay, it's clear that the throughput needs significant improvement before I'll consider turning it back on.
