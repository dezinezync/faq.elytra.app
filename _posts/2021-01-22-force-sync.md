---
title: "Force Sync"
date: 2021-01-22
order: 1
categories: ios,macos
description: Force-sync removes all cached data on your device and resyncs with Elytra API Service. 
---

Elytra caches all your feeds, articles and folder structures locally on your device. However, sometimes, unexpected bugs can come up caused by bad or corrupted cached data. It's easy to quickly get back up to speed when you hit such a situation. 

### iOS 

1. In the iOS or iPadOS app, tap the Settings icon in the Feeds Interface. This will open the Settings modal. 

2. Here, you have two options:
	- You can do a full resync by tapping on the "Force Re-Sync" row. This will clear **all** cached data and download fresh data from the API. 
	- You can do a partial, feeds only resync. This will clear the Feeds & Folder caches and download them again. Articles which have been cached are not removed. 
	
### macOS 

1. While running the macOS app, from the menu bar, click on the File menu.

2. Here you have three options:
	- You can do a standard Refresh which will check with the API for new articles and changes. 
	- You can hold down the option <kbd>⌥</kbd> key to do a Force Resync. 
	- You can hold down the option <kbd>⌥</kbd> + Shift key to do a partial, Feeds only, Force Resync. 
	
You should do a Force Resync when you notice:

- that some of the feeds you added on another device are not appearing on the device you're currently using. 
- a mismatch between the unread count on your device. 
- that some feed preferences aren't being saved. 
- that the folder structures are incorrect. 
	