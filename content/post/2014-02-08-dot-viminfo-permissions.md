---
categories:
- vim
comments: false
date: 2014-02-08T15:48:36-08:00
title: .viminfo permissions
type: post
---

I wondered why my Vim command history wasn't being preserved between sessions.

Root cause: `~/.viminfo`, for whatever
reason, was owned by root. I deleted it, restarted Vim, and all is now good.
