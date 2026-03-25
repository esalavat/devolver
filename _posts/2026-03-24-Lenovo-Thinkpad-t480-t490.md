---
title: "T490: The Best Machine I've Owned"
date: 2026-03-24
layout: post
---

As many developers have experienced, I was running out of RAM and drive space on my base model MacBook Air. I had to run
```
docker system prune
```
every time I switched between projects. This would free up about 8 gigs, but it meant that going back to any of those projects would trigger gigabytes of Docker image downloads all over again.

One solution would be to just buy a newer MacBook with more memory and a larger disk, but I have a problem parting with my money. I was definitely not going to give Apple $1200+ because I didn't opt for the $200 upgrade when I bought my machine.

### The Solution?

That's where my other infatuation (pretending I know Linux) brought me to buying a 7+ year old Lenovo Thinkpad.

If you Google Linux at all you'll be inundated with articles and videos touting the T480 as the ultimate Linux machine. There are tons of videos like [this one](https://youtu.be/kiGibwaOitQ?si=SZ0q03xui-4tZkYd) hyping it up. They're old, but have a cult following for their repairability, great keyboard, and out-of-the-box Linux compatibility. They're also commonly found for under $150 on eBay. 

### The Hunt

I spent the next 3 weeks complaining about my Mac and occasionally opening up eBay and searching for T480s, old Intel MacBooks, mini PCs, etc. I could never bite the bullet. They were all either too expensive or too junky.

Then I decided to enlist Gemini AI in my search. I started feeding search result URLs to Gemini and asking for the best bang for the buck. It was awesome at guiding me to a great machine.

First of all, I wanted 16 gigs of RAM and 512 gigs of storage. A 13" screen is too small, 14"-16" is ideal. A good battery, or a replacement battery if I must. Most people who end up getting a T480 have to buy RAM, a new NVMe drive, and a new battery to get something like that. After parts and the initial purchase, that $150 laptop becomes a $400 hobby project.

### The Find

Gemini told me to look at the T490. It's not as repairable as the T480, but it's got a better screen. It's newer and could have a better battery. The best part is I found a 16 gig, 512 gig, 14" model for under $200. The machine I ended up getting is fully working and has a battery with a cycle count of only 23.

### The Setup

I tapped into Gemini once more to help me decide on a distro and set it up. I ended up with Fedora Workstation. It's super easy to install, very modern, and macOS-adjacent. VSCode, Ghostty with Starship, Node, Docker — I'm good to go. I even got spotify_player, a TUI for Spotify. I don't need RAM being eaten up by a GUI just to play some songs.

![My T490 setup]({{ '/assets/images/posts/2026-03-24/spotify_player.png' | relative_url }})

### My Opinions

This is the best computer I've ever owned. It's light and sturdy, it's got a decent screen, it has tons of ports, it was only $200, and it's got double the RAM and storage of my $1200 MacBook Air.

But the best thing about it by far is the keyboard. It's the best keyboard I've ever felt on a laptop. That alone is reason to buy one.

On top of all that, Fedora is super clean and snappy. I installed some battery manager thing and the battery life is nuts. It lasts all day.

![My T490 setup]({{ '/assets/images/posts/2026-03-24/fedora.png' | relative_url }})

### Conclusion

I think everyone should get one of these things. They're cheap and abundant on eBay, they have great keyboards, and Linux rocks. And you don't need to fixate on the T480 — newer ThinkPads like the T490 or T14 are just as good, if not better, and can be found for similar prices.