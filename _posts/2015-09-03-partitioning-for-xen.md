---
isBasedOnUrl: 'content://x-text:06a2a20a-74e7-4b90-b33e-6f49da5b7de9'
inLanguage: null
starred: false
keywords: []
description: |-
  {% include dogfood/title.md %}
  As I mentioned in my previous post, I am a bit worried about getting
  the configuration right for my host domain. The three-hour s
name: partitioning-for-xen
layout: post
title: Partitioning for Xen
time: '2007-06-17T20:37:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:36:15.297Z'
dateModified: '2015-09-03T10:35:27.878Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-partitioning-for-xen.md
published: true
url: partitioning-for-xen/index.html
_type: Article
_context: 'http://schema.org'

---
# Partitioning for Xen

As I mentioned in my previous post, I am a bit worried about getting
the configuration right for my host domain. The three-hour session I
had with the alternative installer does not help a bit. It seems that
I am trying to do the impossible.

So what exactly is impossible then? I am currently installing my
desktop PC that has two 120GB P-ATA disks and four 400GB S-ATA disks.
First of all I want a safe root partition. The root does not have to
be the size of Texas, about 10GB should do. RAID1 on the smaller
drives feels like a good option. I will use the rest for something
important and want to partition the space later. LVM sounds
resizable.

I want to encrypt everything. LUKS can do that. The partition table
is more important than it is sensitive. That suggests encryption per
partition. That also allows a more fine-grained access control. I
want to configure the bigger disks as a RAID5 array for maximum
capacity.

Let's do the math then. My primary use for this computer is to use it
as a desktop. X should be there. LAMP should stay out. Ubiquity does
not support LVM or RAID at all (didn't find it when I last checked).
Nothing at all supports encryption. I can do that with FUTURE any
time, can't I? Hence alternative desktop CD it is.

No way! When I get past the somewhat hairy procedure of removing all
LVM and RAID arrays, install a language pack for a natural language
and think that everything might be ok, I hear something that makes me
shake in terror: Iä, iä, LILO F'tang. Someone has summoned the
ancient bootloader from R'lyeh. I have no other choice. I Want to be
eaten first.

After the first wave of terror I see that the computer boots up
properly. I try to run FUTURE. It crashes because I have obviously
made some terrible mistake and /boot cannot be moved to another mount
point.
I type halt and carefully pronounce the word (note to self: this is
the first time you use the F-word in this blog) flipper. I think
about the happy faces in the cover of the LiveCD. They must be on
drugs. This has ceased to be fun.

Why on earth would an alternative desktop enforce the use of LILO?