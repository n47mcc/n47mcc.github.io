---
layout: post
title: "How I Set Up a Rails Development Environment"
description: "In which I brain dump on creating a Rails dev machine"
categories: tech
tags:
- rails
- howto
published: true
---

In which I brain dump on creating a Rails development machine:  

Part 0: A Preamble
-------------
Full Disclosure: I only started learning Rails a few months ago (June 2011) so these steps are only what works best for me and do not in any way represent what best practices should be.  

I develop in both OS X and Linux environments so some these steps will pertain to both, but I will try to note any non-obvious differences as I encounter them.  

I use postgres as my backend because I like to have the option to (even more) easily push my code up to [heroku](http://heroku.com) when ever it strikes my fancy.  

Part 1: Install Things
-------------
Xcode: [Install it from the App Store](http://itunes.apple.com/us/app/xcode/id448457090?mt=12)  


Homebrew (OS X):  

    $ /usr/bin/ruby -e "$(curl -fsSL https://raw.github.com/gist/323731)"

Ruby Version Manager:   

    $ bash < <(curl -s https://raw.github.com/wayneeseguin/rvm/master/binscripts/rvm-installer)

Add this line to the bottom of your .bashrc/.zshrc:  

    echo '[[ -s "$HOME/.rvm/scripts/rvm" ]] && . "$HOME/.rvm/scripts/rvm"

Install your preferred version of Ruby:

    $ rvm install 1.9.2
    $ rvm use 1.9.2
    $ ruby -v
    $ which rvm

Install bundler:  

    $ gem install bundler

Install rails

    $ gem install rails

TODO: postgres =(
