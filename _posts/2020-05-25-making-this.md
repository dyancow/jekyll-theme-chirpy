---
title: What I Learned From Making This Website
author: D Niu
date: 2020-05-25 19:02:02 -08000
categories: []
writing: []
---

This [website]((https://chirpy.cotes.info)) is based off Chirpy, a themed Jekyll project.

### 1. Design is HARD

I spent an embarassingly long time trying to use emojis as bullet points in my about page. By the time I was manually adjusting the dimensions of emojis to call them in the markdown, it was too late. I've always known there was quite a bit of distance between a simple envisioned layout and the actual development process, but it's more of a chasm when you don't pick your battles wisely. Even just removing the search bar from the top bar was a task that required quite a bit of digging!

### 2. Be realistic with your tools

All the posts and side pages of this website theme are markdown pages. As mentioned with the emoji fiasco, I was trying to add too much flair to something designed for simplicity. I had even thought of incorporating animations à la Javascript on certain pages. But I should've spent more time and realized that the directory of the website abstracted javascripts away into a [specific section](https://github.com/cotes2020/jekyll-theme-chirpy#directory-structure) of the code.

### 3. Check how it displays on mobile first

If you look at the respository for this website, you'll notice that the date it was created is after this post was originally marked as created. That's because this current bullet was added during the actual publishing of the current website, while everything else was written long before that. I was so excited that the site looked the way I wanted to that I stuck the link in my instagram bio, only for it to open up to a completely empty website. Turns out that some of the components I removed were pretty integral to the mobile user experience, so I decided to start over and test more often during sprint 2.

### 4. Maybe "no code" is the way to go...for speed

Before deciding to use Github pages and a Jeykll-style blog theme, I considered no-code solutions for a personal website; like Squarespace, Wordpress, or even [**Notion**](https://medium.com/@deaduramilade/building-my-website-in-notion-the-pros-and-cons-8cb04f814b1d), my one stop shop for productivity. However, I really appreciate the work Cotes did with this theme and had fun during the process of customizing it. Two major takeaways were cdn links for style and better ways to separate style, layout, and scripts. The previous highlight of my web development career was making an ASP.Net MVC app focused on functionality and performance, so it was refreshing to use a more modern and well-organized stack.