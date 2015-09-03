---
isBasedOnUrl: 'content://x-text:ae9671f4-a3b7-4cc5-aa23-3909db2feb28'
inLanguage: null
starred: false
keywords: []
description: ''
name: outsourcing-music
layout: post
title: Outsourcing music
time: '2007-05-17T14:33:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T11:03:17.197Z'
dateModified: '2015-09-03T11:00:03.982Z'
sourcePath: _posts/2015-09-03-outsourcing-music.md
published: true
tags:
  - ''
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
url: outsourcing-music/index.html
_type: Article
_context: 'http://schema.org'

---
# Outsourcing music

I am having a day off from everything. These are the days I want to
listen to music all the time and take it easy. Yesterday I needed to
configure an icecast server to help a friend in his hacking project.
When I got it working, it wasn't needed anymore. Also, the server
kept requesting credentials and I decided to upgrade to
[icecast2][0]. I was going to stop
there but the Ed Rush gig I was going to see was canceled. I ended up
streaming some music to my friends. My somehow unstable desktop
crashed while I was streaming. I restarted and it must have been
after 5 a.m. until it crashed again.

I wasn't quite happy with my xmms + liveice-ng + icecast2 streaming
in the first place but I decided to outsource my music playback to my
more stable server. This was not the first time my desktop crashes
when I am listening to music. I uploaded some music to my server and
configured liveice to run in shout mode. I was happy, until I wanted
to skip a track. I spent some time Googling for different solutions.
Most of them seemed to be for Windows and the others had to be
plugged into /dev/dsp. Then I found a
[blog post][1]
that solved my problem. I had heard of
[mpd][2] before but somehow I had
forgot about it as well.

I have been really frustrated with icecast1 many times before. The
access control is hardly documented and nothing seems to work out of
box. The init.d script that comes with Ubuntu still seems to fail
restarting icecast2 every time but at least all I had to do was to
configure the mountpoint and change some passwords. To me, mpd is
still the cherry on top. It gives me an endless stream of music
without me actively intervening. This is the way I am going to listen
to my music from now on. I still haven't had the time to configure a
VPN so I could bring my music to the office as well.

[0]: http://www.icecast.org/
[1]: http://www.omskakas.se/2006/06/your-own-internet-radio-station-with-mpdicecast.html
[2]: http://www.musicpd.org/