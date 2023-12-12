---
layout: post
title:  "Home Setup?"
date:   2023-12-06 13:10:42 +1030
categories: blog
---

I'm going to write a whole blog post about my janky home network setup and everything that hangs off it. Why am I writing this? Well it's an easy topic, and I fancied it so now you have to read it I guess. 

## HLD

There is actually very little in the way of networking in my house, at least compared to most people I've met in this industry. Here's a very simple diagram;

![Home Network Diagram](/assets/images/home_network.jpg)

Hanging off of this are a number of wireless devices, 29 according to my router, ranging from laptops to security cameras. 

## Network Stack

I am incredibly ashamed to say that the router and AP are actually a Netgear system, specifically the very easy to say *"Nighthawk Dual-Band WiFi 6 Mesh System AX3000 2-Pack (MK72S)"*. Before you complain though I should point out I got these almost for free, and I get pretty good wireless coverage all over my house.

In terms of management there isn't all that much I can do with this system, the most I've been able to do is split off a seperate 2.4ghz network to hold all my Wifi <6 and IoT devices. This made a small performance difference that was only really noticeably when doing latency and jitter sensitive things like streaming a game via GeforceNow. 

Sitting in between these two devices, that live at either end of my house, is an unmanaged TP-Link 5 port switch. It was $15 off Amazon and seems quite happy forwarding traffic at 1Gbps without needing a fan and taking up about as much space as a can of tuna. Sure I could use something fancier, but why would I?

One final thing the diagram doesn't really make clear, is the idiotic spot NBNco have chosen to locate my NTD. It's in my **BEDROOM**. This means I can't have a device with a fan in it if I want to sleep, and I've also put tape over the LED's on the router and also on the NTD. Luckily an electrician friend of mine was able to run some Cat 6 over to the opposite end of the house so I was able to setup the rest of my stuff and an extra AP outside of the bedroom. 

## Media

As you can see I have a NAS, it's a simple single bay Synology I got for 40% off with a 12TB disk in it. All it really does is hold some backups, run a Plex server, and store my *Very Legitimate* media hoard. It's very quiet, doesn't draw much power at all, and since it doesn't need to do any transcoding it does a terrifc job of running Plex. 

Beyond the NAS, I have a spare "gaming" laptop that I use as a HTPC. It has enough grunt to play most games at 1080p without issue which divides nicely into a 4K TV that I sit too far away from, and it happily runs the Windows Plex app (hence no need to transcode). 

## IoT

Somehow, I've ended up falling into the Ring/Echo ecosystem due to me finding things on sale. Due to never ending problems with our local postal service I have cameras monitoring the whole front of the house + a Ring doorbell - this has been very useful when catching Australia Post pretending to attempt delivery, stealing parcels (yes this really happened), and mishandling parcels after we've logged complaints about them. I also have two more cameras in the yard, one watching the side gate and the other keeping an eye on a tree that a family of Doves and family of Eurasian Blackbirds have taken up residence in. The bird cam has been very helpful and may have saved at least one chick's life after I spotted that it had fallen out of the nest, not to mention the siren function on it that has permanently scared away the neighbours cat. 

I've also dropped down a few lamps with LIFX smart bulbs in them. These light up a couple of rooms on a schedule with a tint appropriate to the season, and also one extra light in the garage that I've scheduled to turn on when it's bin night - very handy!

## Other Junk

Finally, as mentioned earlier I have a bevvy of other random devices I've accumulated;

- My main computer, a Beelink SER5 (5800h, 32GB, 500GB)

- My laptop, a heavily upgraded and refurbished Thinkpad T480

- My tablet, an iPad Mini 6th Gen

- My iPhone, a 15 Pro

- My other phone, a Samsung Galaxy Fold 5 (don't laugh, I swear I use both of them)

- My consoles, a PS5, and a Switch

- My Steamdeck, that I never use

- A gaming PC I'm slowly moving off of, and trying to sell

- And, my work laptop

Believe it or not, this is fewer devices than I had six months ago. 

I'm slowly shrinking my gaming hobby, or maybe more accurately; reducing it's presence in the house. One of the main reasons I've moved to a Wifi 6 setup is to facilitate better quality streaming - GeforceNow is almost indistinguishable now from running on bare metal. Being able to stream Starfield to my tiny little NUC-sized Beelink, and running it at 3440x1440 on Ultra is amazing and it doesn't even cause the fan to spin up. 

## Conclusion

Looking back, my home network has evolved significantly from a tangle of wires to a streamlined, efficient setup, mirroring my journey from a gaming enthusiast to a more casual gamer. The shift towards a Wi-Fi 6 network has not only decluttered my space but also enhanced my gaming experience, proving that sometimes less really is more.