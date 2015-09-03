---
isBasedOnUrl: 'content://x-text:e2b93db9-e759-439a-a2a9-e66bb2f9670b'
inLanguage: null
starred: false
keywords: []
description: |-
  {% include dogfood/title.md %}
  I have once again installed my laptop at work. I don&#39;t usually report
  such incidents. This time it was way too easy to not to
name: encrypting-ubuntu-someday-somehow
layout: post
title: 'Encrypting Ubuntu someday, somehow'
time: '2007-05-14T18:10:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:36:15.542Z'
dateModified: '2015-09-03T10:32:12.155Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-encrypting-ubuntu-someday-somehow.md
published: true
url: encrypting-ubuntu-someday-somehow/index.html
_type: Article
_context: 'http://schema.org'

---
# Encrypting Ubuntu someday, somehow

I have once again installed my laptop at work. I don't usually report
such incidents. This time it was way too easy to not to mention. I
don't know if there was decent documentation for encrypting the root
partition for Ubuntu Edgy. I know there is some documentation
somewhere for Feisty, but I didn't actually find it easily among the
first results of my single Google search. Instead I read the
initramfs scripts and learned to give the correct boot parameters. I
still didn't find out how to encrypt my swap and still be able to
hibernate.

Encryption has for a long time been on top of my wish list for
Ubuntu. It seems that the actual boot scripts are in place, even
though they remain in the universe repository. Not getting my own
scripts for encryption every time surely helps me a lot but I still
hate installing a new system via debootstrap because there clearly
is no way of getting the initial configuration right. Meeting Paul
Sladen at [Assembly Winter][0]
computer event increased my cravings as he convinced me to try to
power management on my laptop. My view of power management changed:
this time it seemed to work. Now I want hibernation for my laptop.

The state of encrypted root partition and swap seems closer than
ever. Installing on an encrypted partition clearly isn't done yet and
the package is still floating in the universe. I still feel excited.
These baby steps prove that someone has been trying to solve my
favorite problem. Having the computer not crash when I close the lid
also was something that brought a smile on my face. It has been two
weeks and I am still waiting for the inspiration to look into swap
encryption. I wish I had the time and will power to solve this issue
once and for all. Making different scripts for different versions of
Ubuntu just doesn't work.

[0]: http://www.assembly.org/