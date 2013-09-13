---
layout: post
title: "A New Start"
description: "A new start for my personal interwebs prescence."
categories: Jekyll
tags:
- Jekyll
published: true
---

Blogs have always been a problem for me. I go into it never expecting to
post often which I feel to be a realistic expectation. What I fail to
recognize each time though is my inner tinkerer. Being a geek I find
myself hosting my own blogs. My own Wordpress instances running on my
own Virtual Private Server. And inevitable I end up tinkering with some
other part of the VPS which causes my personal website/blog to go
crashing down. And when that happens, I am usually so absorbed in some
other project that I fail to perform then necessary maintenace on my now
offline blog. Now I feel that I have found two good solutions to this
problem.

## Jekyll

Wordpress installations are complicated. Granted, they are easy to
install but that ease of use evaporates in the face of the endless
stream of security updates. Furthermore, the configuration necessary for
the setup I have is not exactly straight forward, and doesn't seem to be what Wordpress was originally designed for. However, wordpress is great for quickly and easily
creating new posts, which can be a little challening with a straight up
roll-your-own solution.

[Jekyll](https://github.com/mojombo/jekyll/) is a "blog-aware, static
site Generator" written in Ruby. Using it I can write my posts in
markdown and generate a new website with my new content automatically
inserted into static web pages. This is great for two reasons. I get the
benefit of having a really easy to use content generation system, but
get the additional benefit of a 'roll-your-own' static website. This is
crucial to the second part of my solution.

### nearlyfreespeech.net

[nearlyfreespeech.net](http://nearlyfreespeech.net) is a ridiculously cheap static web host. There's no reason why I couldn't host my static content from my own servers, but as I said above, I have a tendency to break those. Now I can host my content on nearlyfreespech.net and gleefully break my Linux boxes as often as I like. It's perfect!

### Other Stuff

I can also version my blog using git, and deploy is using some git
hooks. As far as I know, that is not possible in a wordpress
installation. Being able to write and upload a blog post right from the
command line is just really cool, it pleases the hard core Linux user in
me. =)
