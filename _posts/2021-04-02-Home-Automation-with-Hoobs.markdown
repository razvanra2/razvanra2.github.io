---
layout: post
title:  "Hoobs: The Hackintosh of Smart Homes"
date:   2021-04-02 17:24:50 +0300
categories: jekyll hello
---
I want to blog about those kinds of software engineering challenges that seem odd.
This is one of the first ones that came to mind.

~~I'm a big fan of home automation.~~ That's a lie. I used to hate home automation. I only kinda like it sometimes now.
Let me explain.

The IoT and Home Automation market is really fragmented right now. There are multiple platforms: Google, Amazon,
Siri, IFTTT, Samsung etc. On top of those, there are competing standards and technologies - WiFi, bluetooth, ZigBee and other
various radio protocols. For all of those, there are adapters, hubs, plugins and seventeen different apps, roughly.
It's a headache. None of them are perfect and all of them have at least some annoying thing about them that makes you
not want to spend your money on them.

I recently switched to the Apple "Ecosystem" (TM). I got a mac because I needed it and was left without a phone earlier this year
and had to buy one - of course I got the iPhone. Next came the air pods because my buds broke and to top it all of, I got
the apple watch in october to convince myself to run (and it actually worked!). Oh, and I had an iPad from 2019 because it's
the only decent tablet you can get.

So now being knee deep into the ecosystem, I was really frustrated with how hard it was to control my smart devices (only TVs at the time)
wit my iPhone. That when I found out about [Hoobs](https://hoobs.org/).

Apple offers their own smart home app. HomeKit and "Home" on your iPhone (if you didn't uninstall it like most people) can control
smart appliances. The only problem is, out of all big "smart home" platforms - Apple/Siri/HomeKit is the least popular out of the big players.
Way more devices are sold with Alexa and Google Assistant compatibility than with HomeKit so buying home appliances for the Apple Home (TM)
is a hard and frustrating process.

Enter Hoobs. Hoobs is a smart home "bridge" that you can flash yourself to any computer/server, but it's really meant for the
raspberry pi. Once installed and connected to the internet, you can install plugins to it, plugins that can help Hoobs (your raspberry pi)
to detect smart devices on your network. I initially thought there would only be a small number of plugins for Hoobs, most of which I wouldn't
care for, but in fact, you'd be surprised how many there are and how useful they are. The first ones I installed were
[a plugin for Samsung Smart TVs](https://plugins.hoobs.org/plugin/homebridge-samsung-tizen) and one for [Roborock](https://plugins.hoobs.org/plugin/homebridge-xiaomi-roborock-vacuum).

I use the Smart TV plugin to control my TVs and link the apple virtual remote to them, a feature theoretically only available
for apple tv and select smart tvs (which cost $$$). Using HDMI-CEC and advance automation, I can even start up my PS4 and Nintendo, from my
phone, from anywhere in the world. Of course, there is no reason to do it, but it happened to me more than once to leave my home and forget
if I did shut down my consoles/tvs. The all-in-one Home app with Hoobs integration was really helpful in those cases.

The one for Roborock I use all the time. I don't enjoy vacuuming myself and further more, I don't enjoy the sound of vacuuming.
Wouldn't it be perfect if someone cleaned our homes when we weren't there? Well, that's exactly my life since I got this plugin.
I set Roborock on a schedule in Apple Home, and now it vacuums when I'm not at home. It's amazing.

They both worked amazingly well. In fact, the only problems I ever had with Hoobs or its plugins were caused by me "holding it wrong".
It's been reliable to a fault in the past year.

Since getting Hoobs, living with the apple smart home ecosystem was much better. I also got a natively supported HomeKit thermostat and
had an amazing experience this winter with it - it saves you from all of those "oh, did i turn the heating off?" moments and also all of those
"i need to turn on the heating _now_ or I will freeze" moments.

I'm really looking forward to adding more accessories. My next buy will probably be an adapter for the AC in the summer.
I've also been looking into lights automation, but I'm not sure if I like any brand enough to invest in it for the moment.

That's it, that's the blog post. If you're in the apple ecosystem, give Hoobs a try. You might not now how many devices in your home
you can control with it.



