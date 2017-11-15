---
layout: post
title:  "Open-Graph"
date:   2017-11-15 06:02:43 +0100
categories: Open Graph HTML head metadata meta
---

**Open Graph**

Social media is growing more than ever, and it'd be hard to guess ten years ago on how big social media would be in ten years. More and more things are shared everyday, wether it is a picture, song or a website, and that's where __Open Graph__ comes in. 

Facebook for example has a built-in way of sharing websites if you haven't done any pre-work and let's you take one of the pictures on the site as a thumbnail. A more professional way of working with this is by specifying on what should be shown when sharing your website on social media.

I did this by changing the 

			<meta property="og: title">
			<meta property="og: type">
			<meta property="og: url">
			<meta property="og: image">

tags to something pre-set and relevant. In my case for example I used a plugin for jekyll called [seo tag](https://github.com/jekyll/jekyll-seo-tag) that handles these different og properties. Then I set the picture on the about page as my thumbnail manually.