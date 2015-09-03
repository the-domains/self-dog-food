---
isBasedOnUrl: 'content://x-text:490868d7-5cb1-4691-b081-3f37445c43b0'
inLanguage: null
starred: false
keywords: []
description: "{% include dogfood/title.md %}\nAs mentioned earlier, I installed Gutsy Goatse on my Dell D630 \nlaptop. I was a bit bothered with the soundcard not working anymo"
name: running-gutsy
layout: post
title: First aid for Dell D630 running Gutsy
time: '2007-09-28T08:07:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:36:14.557Z'
dateModified: '2015-09-03T10:34:39.369Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-first-aid-for-dell-d630-running-gutsy.md
published: true
url: first-aid-for-dell-d630-running-gutsy/index.html
_type: Article
_context: 'http://schema.org'

---
# First aid for Dell D630 running Gutsy

As mentioned earlier, I installed Gutsy Goatse on my Dell D630 
laptop. I was a bit bothered with the soundcard not working anymore. 
It appeared that alsa 1.0.15rc\[123\] should work. I packaged it for 
amd64 kernel 2.6.22-12-generic and uploaded all packages made in the 
process to my [package
directory][0].

I hope this helps the rest of you.

Edit: I just heard that suspend to RAM does not work with rc2 or 
rc3\. I will make packages out of rc1 later on. For now my nvidia 
driver or something else stops me from suspending in the first 
place.

Edit 2012-06-28: The link is long past gone and this post remains
just a historical reference.

[0]: content://x-text:490868d7-5cb1-4691-b081-3f37445c43b0/software/packages/alsa/