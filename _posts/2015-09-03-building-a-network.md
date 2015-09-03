---
isBasedOnUrl: 'content://x-text:8ed57221-7b65-4fbd-b997-a98ff688ddaf'
inLanguage: null
starred: false
keywords: []
description: "{% include dogfood/title.md %}\nA RAID5 partition went haywire and I lost 1.2TB of data. I don&#39;t feel\nas bad as I did last year when I lost one tenth of the "
name: building-network
layout: post
title: Building a network
time: '2007-06-16T17:51:00.000Z'
categories:
  - earlypenguin
published: true
status: draft
author: []
datePublished: '2015-09-03T10:36:16.404Z'
dateModified: '2015-09-03T10:35:37.348Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-building-a-network.md
url: building-a-network/index.html
_type: Article
_context: 'http://schema.org'

---
# Building a network

A RAID5 partition went haywire and I lost 1.2TB of data. I don't feel
as bad as I did last year when I lost one tenth of the amount. I
think I have learned something. I have made some manual backing up
since then and I still have the drives I replaced with the current
drives a month ago. Now I have a good reason to completely rebuild my
desktop. I am planning to run Xen and play with unionfs. This enables
me to play with virtual servers which in turn hopefully paces up some
projects of mine (yes, the AoEPIA and onionpeel for example). I am
also installing Xen on my router box and actually rebuilding my home
network pretty much from scratch.

I have decided to do this the Right Way and documenting everything
the way a professional would do. While I am at it, I will document
everything on this blog. Most of the things I have tried before and I
know my ways with. I am a bit worried about not getting the host
system right the first time. The size of the root partition worries
me a bit.

Step 1: Download Ubuntu Alternative installation CD.