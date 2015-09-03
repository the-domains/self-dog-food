---
isBasedOnUrl: 'content://x-text:b85c0668-8f34-4927-8071-eee264e5158b'
inLanguage: null
starred: false
keywords: []
description: |
  {% include dogfood/title.md %}
  As I mentioned in my earlier post, I fought a battle with Compiz
  today. I think some notices might be useful for others as well.
name: compiz-tips
layout: post
title: Compiz tips
time: '2007-09-26T21:43:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:36:14.478Z'
dateModified: '2015-09-03T10:33:26.596Z'
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-compiz-tips.md
published: true
url: compiz-tips/index.html
_type: Article
_context: 'http://schema.org'

---
# Compiz tips

As I mentioned in my earlier post, I fought a battle with Compiz
today. I think some notices might be useful for others as well.

1. In the newest version using --Up for the
window selection thingy makes Compiz crash pretty easily. That is
because Compiz tries to change the workspace when selecting
windows.
2. Using desktop-effects makes a mess. Don't do it. It makes some
settings that you don't want and reduces the sides of the cube to
one.
3. The gnome-compiz-manager started only on the second try every
time. It tries to start a new compiz and that fails obviously when a
new one appears. The manager does some nice things and is a good
thing for the basics. It still does not have all the features
necessary for a full configuration.
4. There is nothing better than gconf-editor. First I used it for
adding the workspaces that desktop-effects destroyed. I poked this
and that and now I have a transparent hexagonal desktop. There is
also the water effect which is rather strange but annotation is
something I could really use in case I am presenting something.
5. In case you have trouble with switching workspaces like I did, you
should try the following. In case your workspace is double-switched
or moves more than once per key press, you probably have a key
mapping conflict. By design plane and cube are mutually exclusive as
well as metacity and both of the former. However the wall plugin may
do some damage. I didn't have the gconf settings for both left and
right buttons. After I found out that there was a binding for 
--Left in the settings I made a new key with
left replaced with right and marked them both Disabled. 
The keys are:

/apps/compiz/plugins/wall/allscreens/options/left\_key
/apps/compiz/plugins/wall/allscreens/options/right\_key

I also uploaded my
[compiz configuration][0]
to my
[configuration directory][1].

Note 2012: The links are long since obsolete.

[0]: content://x-text:b85c0668-8f34-4927-8071-eee264e5158b/software/configuration/compiz/compiz_conf_280907.xml
[1]: content://x-text:b85c0668-8f34-4927-8071-eee264e5158b/software/configuration/