---
isBasedOnUrl: 'content://x-text:94d28ab7-62fe-4aa6-b230-33e79cae2b3f'
inLanguage: null
starred: false
keywords: []
description: "{% include dogfood/title.md %}\nI have been having a real vacation for a change. I have tons of thing \nto do and some of them I have had to drop from my schedule"
name: two-steps-forward-and-only-one-back
layout: post
title: Two steps forward and only one back
time: '2007-06-27T09:22:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:36:15.377Z'
dateModified: '2015-09-03T10:35:11.619Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-two-steps-forward-and-only-one-back.md
published: true
url: two-steps-forward-and-only-one-back/index.html
_type: Article
_context: 'http://schema.org'

---
# Two steps forward and only one back

I have been having a real vacation for a change. I have tons of thing 
to do and some of them I have had to drop from my schedule
completely. One of them is preparing the Party Management System for 
[Assembly Summer 07][0]. I have also taken
some time to take it easy and some to have fun. I even dug up my
dance mat from the basement and I have been taking more steps with
[Stepmania][1] than with my hobby projects.
It's funny how aerobic becomes a perfect hobby for men when you add a
computer and scoring.

First of all I have to apologize to the people behind Ubuntu
installer. One of the seven or so installation options actually
worked. Obviously the OEM (which I used in my previous post) and Live
options are totally usable for my application but the alternative
installation works. The Live option first makes the system slow and
then crashes. It may be due to my display adapter being an ATI but I
am not certain. Safe mode wasn't too safe either.

Next thing to do was installing my favorite tools and Xen. I didn't
do that right away. First there was a problem with the newly created
md and lvm arrays not coming up at boot time. A manual run made
things run smoothly on subsequent boots. Next I had to find out why
my mouse and keyboard didn't respond after installation. I have a set
that works over Bluetooth and quite soon I noticed that HID is not
turned on by default and the Logitech BT dongle that usually gets an
Oscar from being a completely good USB hub had gone dark. Turning on
HID and pairing the devices worked. Having no secondary keyboard and
no SSH server on made me scratch my forehead for a while. I summoned
an uncursed USB keyboard of battery power and that was it. I run
FUTURE and it worked like a charm. There have been reports from
others that it works somewhat OK.

From my previous adventures in the kingdom of Xen I know that there
is a package called
[ubuntu-xen-server][2]
somewhere in the universe and even a
[ubuntu-xen-desktop][3]
had been there. How wrong could I be! The package is named
[ubuntu-xen-desktop-amd64][4]
in the amd64 repository and the server package is completely missing.
All of these meta packages are a wee bit different. The desktop
packages contain exactly the packages as the desktop packages. Why
not making a dependency instead of copying? It is no wonder that
these packages are still in the universe. I made a
[patch][5]
and a
[package][6].

Edit 2012-06-28: The links are long since expired as well as the
packages. Eventually there became a way to install Xen on Ubuntu as
Xen got easier. This post is here for historical reference.

[0]: http://www.assembly.org/
[1]: http://www.stepmania.com/
[2]: http://packages.ubuntu.com/feisty/base/ubuntu-xen-server
[3]: http://packages.ubuntu.com/feisty/base/ubuntu-xen-desktop
[4]: http://packages.ubuntu.com/feisty/base/ubuntu-xen-desktop-amd64
[5]: http://www.earlypenguin.fi/software/patches/xen-meta-0.0.1-amd64-server.patch
[6]: http://www.earlypenguin.fi/software/packages/ubuntu-xen-server-amd64_0.0.1-2ubuntu4_amd64.deb