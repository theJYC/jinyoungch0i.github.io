---
layout: post
title:  "jinyoung.xyz"
date:   2020-09-16 02:36:11 +0900
category: dev
---

<img src="{{site.base_url}}/dev/assets/images/xyz.gif" alt='blog preview' width="328">

[jinyoung.xyz](https://jinyoung.xyz/){:target="_blank"} is a custom-built site that is currently hosted on a Netlify server. It runs on Jekyll, a static site engine built in Ruby, HTML5, SASS, and CSS3.

Although I had been thinking of building my first site with Python (my native language) and Flask, I came to understand that Github Pages, which had hosted [jinyoung.xyz](https://jinyoung.xyz/){:target="_blank"} at no additional cost, only supports static websites.

_*Update 11/02/20: I have now migrated the site to Netlify due to privacy concern with regards to exposed API key(s)._

My initial plan was to make a full-fledged CRUD application that connects to a SQLite database, though I concluded that a static website will be a perfect starting point for now. After all, I'm not trying to make the next Facebook; I just want this to be a minimalist platform where I can share my work and growing opinion on programming and other life endeavours. 

While I'm still exploring various avenues to scale jinyoung.xyz, I am happy to have gotten to learn how to deploy a fast and responsive website that also has allowed me to flex my web development muscles (if you'll pardon the CSS pun).

Now, Jekyll came with the default [minima theme](https://jekyll.github.io/minima/){:target="_blank"} though I ended up overhauling much of the existing codebase and to instead put in a hefty amount of custom HTML5, CSS3, SASS, and Liquid code. I think the personal touch speaks for itself. :)

To-do:

- [x] Make site fully responsive across most client devices. 
- [x] Decide whether or not to integrate analytics & SEO 
    - see [On Minimalism](https://jinyoung.xyz/journey/2020/09/20/on-minimalism.html){:target="_blank"}
- [x] Connect site to API(s). 
    - [x] [OpenWeatherMap](https://openweathermap.org/){:target="_blank"}
- [ ] Make the landing page 🇰🇷/🇪🇸/🇧🇷 friendly.
- [ ] Embed images on post entries being conscious of limited repository storage.
- [ ] Compile all featured images onto [photos](https://jinyoung.xyz/gallery/){:target="_blank"}
