---
title: "Home"
date: 2023-02-04T18:19:48+08:00
draft: false
toc: true
---

 [EinkBro 使用說明手冊 中文版](https://medium.com/ereadertips/einkbro-%E4%BD%BF%E7%94%A8%E6%95%99%E5%AD%B8%E8%88%87%E5%B0%8F%E6%8A%80%E5%B7%A7-db9c93b4d890)

## Overview
### Why it's created

As the CPU power is getting stronger, and screen refresh speed keeps improving for E-Ink devices, more and more people start to use E-Ink devices to browse the internet. It’s working; however the experience is not good enough. Existing browsers are not designed for E-Ink devices. So many UI elements are designed for normal Android devices: fancy animations, dimming background when dialogs pop up, etc.

To make a browser suitable for E-Ink devices, two principles should be followed while designing UI interactions:

Fewer repaint counts
Make repaint area as small as possible
So far, I haven’t seen a dedicated browser for E-Ink devices yet. I decided to make one, based on a Github project written by Gaukler Faun. FOSS Browser is a lightweight browser that supports many features, including ad blocking, tab control, gesture control, etc. I took some time to refactor the codes and make necessary modifications to make it more appealing for E-Ink devices. Now it has a lot of useful features for E Ink devices.

### Main features

Now it has following E-ink related features:
* PageUp/pageDown by (touch area / volume keys / onscreen buttons)
* Reader mode (remove headers, ads, sidebars, footers, for easier reading)
* Full text translation mode
* Vertical reading mode (suitable for Chinese and Japanese)
* Content display customization (bold font, font size change, font style change)
* Export web content as epub file
* Tool bar configuration (show/hide actions, or re-arrange order)
* Desktop mode feature
* All icons in high contrast colors
* Refactor most popup dialogs, so that there’s no longer animations.
* Remove gray mask when dialog pops up.

![image](https://user-images.githubusercontent.com/4084738/212552177-4a4f4878-6041-42df-9210-350d48150352.png)

## UI Manual
* [Main UI descriptions]({{< ref "/docs/basic_ui_explanation" >}})
* [Action Menu]({{< ref "action_menu" >}})
* [Toolbar actions and customization]({{< ref "/docs/toobar_actions" >}})
* [Settings]({{< ref "/docs/settings" >}})

