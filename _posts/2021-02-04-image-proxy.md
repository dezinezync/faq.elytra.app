---
title: "Image Proxy"
date: 2021-02-04
order: 3
categories: about
---

Elytra uses an Image Proxy run by [WeServ.nl](https://images.weserv.nl). 

Elytra strips all identifiers which could be used to track you when making requests to it. 

What it does:

1. Say an article embeds an image which is 8MB in size. 

2. When iOS renders this, it becomes 32MB (example). 

3. Say you’re using an iPhone where the screen width is only 375px, and the image is 4000px wide. 

4. The request is routed through the proxy to fetch an image which is only 375px wide, so it’s smaller in size, faster to download and consumes less bandwidth and power. 

If you turn off the proxy option, the full image is downloaded, scaled and resized on your device which increases power and bandwidth consumption, as well as uses more temporary disk space.

Using the Image Proxy is completely optional, entirely upon your discretion. It is enabled by default.
