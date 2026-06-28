---
title: Homelab
slug: Projects/homelab
draft: true
author: John Bloomfield
tags:
 - Homelab
 - Server
---

Since moving into this house in 2018, I have been tinkering with smart home devices, adding a homelab server to host TV show, movies, photos etc.

## Services



## Main server




## NAS

I recently looked into whether I could cut down on the amount of subscriptions I am paying for, even though some of these are paid for by my business, I believed I could self-host some alternatives to not rely on "the cloud" as much.

I had an old [HP ProLiant Gen8 Micro Server](https://uk.pcmag.com/servers/9683/hp-proliant-microserver-gen8) in the loft that I used to use for my homelab, so I looked at getting a 4TB Raid 1 set up to give me some redundancy, so that I could feel a little more confident storing family photos and important data on it.

After numerous videos and research, I settled on TrueNAS, which was relatively easy to get setup using an ISO file on a USB stick, switching the BIOS on the Micro Server to boot from USB and it was all up and running.

### NAS Apps



## Networking & Cameras

After quite a lot of research back in 2018, I settled on [Ubiquiti Unifi](https://ui.com/) for my networking and WiFi access points. It probably wasn't the cheapest option I could of chosen but I think the [CloudKey Gen 2 Plus](https://techspecs.ui.com/unifi/physical-security/uck-g2-plus) had the option of adding a 2.5" HDD as a NVR which was perfect alongside some PoE cameras.

- Router
	- [Cloud Gateway Ultra](https://techspecs.ui.com/unifi/cloud-gateways/ucg-ultra) (UCG-Ultra)
- Main Switch
	- Ubiquiti US-16-150W (POE)
- Garden Office
	- Ubiquiti USW-Flex (4 Port)
- WiFi Access Points
	- 5 x Ubiquiti UAP-AC-PRO
- Controller
	- [CloudKey Gen 2 Plus](https://techspecs.ui.com/unifi/physical-security/uck-g2-plus)
	- NVR
		- 500GB Western Digital WDS500G2B0A 2.5" SATA
- Cameras
	- 3 x Ubiquiti UVC-G3-PRO PoE Bullet IP Camera
	- 1 x Ubiquiti G5 Turret Ultra (Black)
	- 1 x G4 Instant WiFi Camera