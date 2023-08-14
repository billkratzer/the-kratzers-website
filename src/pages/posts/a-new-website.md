---
layout: '../../layouts/BlogPostLayout.astro'
title: 'Website Relaunch!'
pubDate: 2023-08-06
description: 'I just reimplemented my website using Astro!'
author: 'Bill Kratzer'
image:
  url: '/images/blog/macbook_pro_and_coffee.png'
  alt: 'Laptop Cafe image created by Midjourney'
tags: [ "Programming" ]
---

Today marks a re-launch of this website!

Over the years, I have tried several static site frameworks, including [Jekyll](https://jekyllrb.com/) and [Hugo](https://gohugo.io/).   
Both of these frameworks were fun to play with but neither really resonated with me.  
I disliked getting Ruby working properly on my laptop and my Amazon EC2 instance for Jekyll.  

Hugo's online documentation is a mess, and I found the use of Go's templating capabilities to be a major limitation.

Enter Astro!  

[Astro](https://astro.build/) is a modern take on static site generators that takes inspiration with popular frameworks like
VueJS and React, even allowing me to build this website as a series of easy-to-define reusable components.  The bonus
for me is that the Astro website itself uses [Tailwind](https://tailwindcss.com), so dealing with this popular framework is not an afterthought.

I'm looking forward to learn more about Astro and plan to use it on my next big project!
