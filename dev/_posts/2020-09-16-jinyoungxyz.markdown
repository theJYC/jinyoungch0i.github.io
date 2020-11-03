---
layout: post
title:  "jinyoung.xyz"
date:   2020-09-16 02:36:11 +0900
category: dev
---

[jinyoung.xyz](https://jinyoung.xyz/){:target="_blank"} is a custom-built site that is currently hosted on Netlify. It runs on Jekyll, a static site engine built in Ruby, HTML5, SASS, and CSS3. [**Link** to source code](https://github.com/jinyoungch0i/xyz){:target="_blank"}

Although I had been thinking of building my first site with Python (my native language) and Flask, I came to understand that Github Pages, which had hosted [jinyoung.xyz](https://jinyoung.xyz/){:target="_blank"} at no additional cost, only supports static websites (Update 10/31/20: even with the limitations of the static platform, I have been able to integrate dynamic content rendering with JavaScript. As of 11/2/20, I have also migrated the site to Netlify due to privacy issues with exposing API keys in public repositories).

My initial plan was to make a full-fledged CRUD application that connects to a SQLite database, though I concluded that a static website will be a perfect starting point for now. After all, I'm not trying to make the next Facebook; I just want this to be a minimalist platform where I can share my work and growing opinion on programming and other life endeavours. 

While I'm still exploring various avenues to scale jinyoung.xyz, I am happy to have gotten to learn how to deploy a fast and responsive website that also has allowed me to flex my web development muscles (if you'll pardon the CSS pun).

Now, Jekyll came with the default [minima theme](https://jekyll.github.io/minima/){:target="_blank"} though I ended up overhauling much of the existing codebase and to instead put in a hefty amount of custom HTML5, CSS3, SASS, and Liquid code. I think the personal touch speaks for itself. :)

To-do:

* ~~Make site fully responsive.~~ 
    * (^please drop me an email if website looks funny on your device!)
* ~~Decide whether or not to integrate analytics.~~ see [On Minimalism](https://jinyoung.xyz/journey/2020/09/20/on-minimalism.html){:target="_blank"}
* ~~Decide whether to spend time & effort on improving site's SEO.~~
* ~~Connect site to API(s).~~ 
    * [OpenWeatherMap](https://openweathermap.org/){:target="_blank"} for real-time weater data ☀️
* Make the landing page 🇰🇷/🇪🇸/🇧🇷 friendly.
* Embed images on post entries being conscious of limited repository storage.
* Compile all featured images onto [photos](https://jinyoung.xyz/gallery/){:target="_blank"}

I understand that the migration to Netlify's private server means that my blog is no longer Open Source. If you would nonetheless like to contribute or provide feedback, I welcome you to [get in touch](mailto:jinyoungsjourney@gmail.com?subject=[jinyoung.xyz])! :)
