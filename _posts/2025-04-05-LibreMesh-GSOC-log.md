---
layout: post
title:  "GSOC journey with LibreMesh"
date:   2025-04-05
categories: gsoc libremesh openwrt opensource wifi linux kernel
---

`YEAR-MONTH-DAY-title.MARKUP`

Hey hey !

This is my first post to document my journey for **Google Summer of Code 2025**.

After going through the different organisations selected to participate in GSOC 2025, Freifunk peaked my interest (I was just coming back from a trip to Germany and discover about them there) with a special mention for the project proposed by Javier Jorge titled : *Adding Wi-Fi Support to QEMU Simulations in LibreMesh*. 

Linux, QEMU, OpenWrt, all that with a background of a distributed system, all in one project ? All my subjects of predilection all in one project : that's my luck ! 

I was already familiar with different mesh projects such as Meshtastic (lora based mesh network) and obviously Guifi.net but never heard of LibreMesh until now, but I find it a fantastic project and will try to convince my Parisian lora peers to maybe complete their network with a wifi one. 

## 🧠 About the Project

The idea is to bring Wi-Fi virtualization capabilities to LibreMesh through QEMU, using the Linux kernel module `mac80211_hwsim`. This would allow for:

- Lighter, faster, and more flexible testing setups
- Simulating complex wireless topologies
- Reducing hardware dependence during development and CI

This could be a real game-changer for automated testing in LibreMesh — testing routing protocols in various topologies without needing physical devices for each node.

---

## 🔍 Useful Reads

Here are a few resources I found particularly interesting while researching for this project:

- [LibreMesh official site](https://libremesh.org)
- [Emulating WLAN in Linux – Part I: The 802.11 Stack](https://www.linuxembedded.fr/2020/05/emulating-wlan-in-linux-part-i-the-80211-stack)
- [Emulating WLAN in Linux – Part II: mac80211_hwsim](https://www.linuxembedded.fr/2021/01/emulating-wlan-in-linux-part-ii-mac80211hwsim)
- [Guifi.net](https://guifi.net/)
- [vwifi](https://github.com/Raizo62/vwifi)
---

Thanks for reading! I’ll be updating this blog as I progress through — no matter how it ends up I will have learn a lot.

