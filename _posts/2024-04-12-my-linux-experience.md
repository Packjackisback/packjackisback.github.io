---
layout: post
title: My switch to Linux
lead: I am free.
---

When I was 10, my parents decided to get me a Raspberry Pi for christmas. I had very limited experience with anything tech related, but I quickly got Raspbian (now Raspberry Pi OS) onto it.
I was expecting an experience similar to school computers, with almost no lag or processor limitations. You can imagine my dismay when I opened the web browser (chromium). 
I was unable to do the most basic brain numbing activities I had attributed to having fun in my mind, like watching Youtube or playing CoolMathGames. 

I researched ways to improve performance, but nothing seemed to offset the massively underpowered processor. Around that time, I got a book from the library about ["hacking"](https://www.amazon.com/Gray-Hat-Hacking-Ethical-Handbook/dp/1260108414).
As you can imagine, this book went way over my head. I had no experience programming other than messing around in Python and Sonic Pi, but the book involved using Kali Linux, which being the noobie I was, I saw as the holy grail of being a "hacker".
``ventually, I was able to install Kali, which involved downloading Balena Etcher (I didn't know dd existed), and I got Kali booted up. I was in shock. The distro looked complletely different, and ran faster. 

I messed around for a bit, and eventually switched back to Raspbian, having gained a tantalizing look of what Linux could do. Again struggling with hardware limitations, I looked at DistroWatch, and lo and behold, MX Linux was at the top.
MX promised to have a "elegant and efficient desktop with simple configuration, high stability, solid performance and medium-sized footprint", and I was looking for an upgrade. I tried it out, and I was astonished by just how good it was.
It looked good, was really fast, and encouraged configuration. I spent hours configuring it to the very limit of what its tools allowed, and still wanted more. I eventually found you could replace the wm, and that was my first real exposure to the command line.
I installed xfce, and was astonished by just how **fun** it was to use the command line. Typing in commands and changing the computer for yourslef, not changing to meet the computer, felt great. 

Eventually, I messed up the system somehow, and was unable to fix it without a reinstall. I went back to Raspbian, now called RPi OS, and started configuring things to how I wanted. I installed a different DE, and eventually in my journey of customization, stumbled upon the [r/unixporn](https://old.reddit.com/r/unixporn) subreddit. These guys were creating amazing things with all these cool tools, but when I went to install them, I found that I had to build them, as most packages didn't work with the Rpi's architecture. After about 5 packages with dependency errors, I decided there had to be a better way, and I found Arch Linux and its AUR. 

Using the [ArchWiki page](https://archlinuxarm.org/platforms/armv8/broadcom/raspberry-pi-3), I started trying to install Arch. Following the Wiki's steps to the T, I was able to install it. 
I found a guide on how to install LXDE, and was happy with the extreme performance increase. For the first time, I could do what I wanted. I got around to installing i3 with Pywal and had a pretty nice setup.

For whatever reason, I eventually stopped using my Rpi as much, sticking to my config for a while. I would borrow a Laptop from my parent's if I needed it, until when I reahed High School. I then got an old, beat up, 30$ Hp Envy 360x from 7 years ago, with less than 8 Gb of ram, and a 2.1 Ghz processor speed. Still, it was a massive step up. I used Windows for a while, in the mindset that it worked, and was as good as it would get. It was the industry standard, but Windows was using about 2 whole Gigabits of storage at idle. 

Despite crashing regularly, almost 5-6 times a day, I continued to use it because it worked with my games. I messed around with dual booting, but never seriously used my Manjaro installation, as I didn't really like it. I tried configuring Windows, and became very aware of its limitations. I was tired of fighting the bloated, spyware I had installed on my computer, and I longed for the days of my Raspberry Pi. Nothing but sheer laziness and the fear I would break it kept me from freeing myself. 

Eventually, I could take no more. I shrank the partition, and created an Arch Install USB. Following the Wiki, I installed Arch in a few tries, and wanted to keep my system fast, and customizable. I looked for an i3 alternative for Wayland (which I tried on the Rpi) and found hyprland. It installed without a hitch, I customized it, and that's where I am today.

Installing Linux has been good for my mental health. I don't know how to explain it perfectly, but using Windows was a grainy filter on top of my life. I wouldn't go 30 minutes with struggling through the 40% cpu usage from windows, and it seems like a little thing, but the lag just infuriated me. I would boot up my laptop for a class activity, and it would just crash. In comparison, I am legitimately happy while using Linux, choosing what my hardware does. I know what every byte going out of my system is, and I know whatever is running at any given time. I had been living in a cloud of hopelessness, but Linux was truly a source of hope and joy. I know it sounds corny, but I would literally go to sleep, thinking about what I would code or configure on my system.

Again, I know it's a cliche, but Linux set me free.
