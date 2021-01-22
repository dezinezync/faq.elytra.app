---
title: "Feed Preferences"
date: 2021-01-22
order: 98
categories: ios
description: Feed Preferences show list of preferences specific to that feed including Notifications and Reader Mode. 
---

Following on the footsteps of the excellent app, [NetNewsWire](https://netnewswire.com), I've implemented a Feed Preferences interface similar to NNW albeit with some differences. 

You can access this interface by:

- Tapping on the Title View in the Articles List interface. 

- Tapping on the Feed Info context menu item by long tapping on a feed. 

In Elytra, this interface lists the following options: 

### Notifications 

You can turn on notifications for the feed if you'd like to be notified about new articles from that feed. 

Notifications are of two types:

- Local: When the app updates your local cache, it checks for new articles and presents these as a local notification. 

- Push: Certain feeds support Push Notifications (eg: The Elytra Blog, my personal blog linked in the footer) and deliver a push notification as soon as the publisher posts an article on their website. 

### Reader Mode 

- When you swipe to open an article in the in-app browser or tap on the Browser icon in the Article Reader interface, toggling this option on will automatically load the Reader Mode when its available on that page. 

### URLs

This interface also lists the Feed's URL and can be copied by long tapping on it. 

If a website URL is available, that will be listed as well and can be similarly copied. 

----

If you have suggestions for more options, feel free to reach out to me at [support@elytra.app](mailto:support@elytra.app?subject=Feed Interface Suggestion)
