---
isBasedOnUrl: 'content://x-text:be3481a3-6785-42de-a916-959286f9a720'
inLanguage: null
starred: false
keywords: []
description: 'I had to drive to the west coast of Finland through a snowy, um,Finland. The weather was lovely as ever though I didn&#39;t see '
name: comparing-gps-software
layout: post
title: Comparing GPS software
time: '2008-11-26T15:38:00.000Z'
categories:
  - earlypenguin
author: []
datePublished: '2015-09-03T10:49:50.929Z'
dateModified: '2015-09-03T10:44:13.380Z'
tags:
  - ''
authors: []
publisher:
  name: x-text
  domain: x-text
  url: null
  favicon: null
sourcePath: _posts/2015-09-03-comparing-gps-software.md
published: true
url: comparing-gps-software/index.html
_type: Article
_context: 'http://schema.org'

---
# Comparing GPS software

I had to drive to the west coast of Finland through a snowy, um,
Finland. The weather was lovely as ever though I didn't see much
through the heavy snowing on my way down there and heavy rain and
darkness on my way back. However I was in a good mood because I had
my friends from Nokia keeping me company. I know neither of my
friends has any FOSS inside but they are the closest thing I have for
a navigator with a battery that would last the whole trip back and
forth. They are also the only devices that I have a car charger for.
So, my friends E71 and 6110 Navigator were there. On my way to the
coast. Yes, the same coast that is 150 meters from my humble flat,
but on the other side of the country. Anyway, that's when I used the
Nokia Maps bundled with my E71 with a year's worth of navigation as a
service. A friendly female voice and a user interface I won't speak
my mind about. On the way back to the coast, home that is, I used the
Nokia Navigator bundled with the other phone with an apparently
unlimited subscription and a male voice and a bit different user
interface I could not wrap my mind around either.

First of all, I don't quite see how navigation should be a service
and the maps should not. In just about any solution it is free to see
where you stand on the map right now. It is also free to look up odd
places and see a vector illustration which explains nothing at all.
In some solutions it is even free of charge to simulate navigating.
That stands for moving from A to B at a static pace of 50 or 80 km/h.
Imagine the people trying to get to places and while saving money.
Driving less than half the limit on the freeway or someone speeding.
almost triple the speed limit in a suburb. So obviously the route
data is there or can be downloaded there even when you do not have an
active subscription.

So what are we paying for? Updates are the obvious answer. But the
way I am paying for them is strange. I can get the actual data for
free and just flipping the switch is what makes the register go ting.
At least I get updated maps and routes for the pr... wait a minute.
The maps I get for free anyhoo are actually not up to date. I
checked. I started from Espoo and went towards Turku and avoided it
just in a nick of time. There is a motorway which has just been
opened, partly, whose building went overtime due to optimism. Sounds
just like a software project. I had never driven the new part and
thought that my navigator which gets the route from the mighty
Internet will probably give me the right instructions. After making a
U-turn I found that I was dead wrong. While driving along the yellow
plain (according to the navigator) I heard a constant nagging from
the lady shouting instructions. At one point she told me to "Turn
left now, turn right now, make a U-turn" in one sentence. I wanted to
divorce the old hag the first chance I get. So I get outdated data
for my service subscription. I understand a small delay but it's not
like the road that has been built for nearly a decade comes as a
surprise to anyone. It was on the newspaper as well. They would have
got it updated in a week if they wanted to. On my way back the male
voice did the same nagging but the tone was low enough for me not to
notice it most of the time under the groovy beats of the millennium
coming from the radio.

FOSS-navigation should be different. Just like you cannot trust the
data you get from the vendor of your mobile pho... thing, you can't
trust the mapping community. I think it is okay because I am not
paying for it and they can say they told me so if I don't get there
in time. Making maps is simple anyway. Someone drives along a road
with a GPX tracking software and sends in a patch. According to the
theories about community intelligence when more people who drive the
same path, we will eventually get the coordinates right. I can say I
am not an expert on Open Source GPS navigation, however I think I
know what everybody wants. Let's have a killer feature in a software.
When the navigator notices that the car (or biped creature) is on the
white area, start tracking. That's when the lady can stop nagging as
well. It is highly probable that the navigator is wrong and the
driver is right or then there's been an accident and making a U-turn
is not the most expected option. When the driver reaches the
destination, let's ask something:

> "I noticed that you took a detour, would you care to explain it to
> the community?"
> 
> \[Sure\]
> \[Later\]
> \[What detour?\]
> \[Sorry, no\]
> \[That was actually a petrol station\]
> \[Actually the map was a bit off\]

Because the driver is a good bloke, the discussion would go on:

> "Have you got any idea about the name?"
> 
> \[Yes\] 
> \[No\]

Yes, that was the new motorway.

> "How confident are you about the name?"
> 
> \[1 - Just a guess\]
> \[2 - I heard it somewhere\]
> \[3 - Pretty sure\]
> \[4 - Yes, but I am not sure about the spelling\]
> \[5 - Positive, sir!\]"

This information would be recorded to point out possible false
information and on with our story:

> "You were 20 minutes off from any known roads was the speed limit 70 km/h?"
> 
> \[Yes\]
> \[No\]

This was not the case:

> "So it what was it (leave blank if you don't remember)?"

He wasn't speeding, he was squirming:

> "Care to tell me the reason?"
> 
> \[A break\]
> \[Congestion\]
> \[Weather\]
> \[Accident\]
> \[Something else\]

This time it was congestion:

> "Would you say this road is usually congested?"
> 
> \[Always\]
> \[Sometimes\]
> \[No idea\]
> \[Not this much\]
> \[I am just having a bad day\]

After minute of discussion the navigator would say thanks buddy and
schedule the data for upload. If the driver is really proactive, he
might send two-click updates like "I am here because of a traffic
light" and the system might clock the stop. Real time accident and
congestion data might be included. There could be several different
map sources and they could be assigned different precedence levels.

Could this fly?