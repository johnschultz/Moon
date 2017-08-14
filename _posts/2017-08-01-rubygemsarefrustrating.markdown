---
layout: post
title: "Ruby Gems are Frustrating"
date: "2017-08-01 13:11:16 -0700"
tags: ruby jekyll atom
---

Like most things I do, I've decided to make this little blog adventure more
complicated than it needs to be. I'm trying out the `atom` text editor (instead
of my usual love, VIM). I do have VIM-mode installed, so I suppose I'm cheating
a little bit.

There's a nice `jekyll` plugin for `atom`, but I can't get it to run `jekyll build`
properly, and I can't find the console error output so I'm not sure how to debug
the problem. I think the issue is stemming from the fact that it's not invoking
`jekyll` with `bundler` so there are some dependency issues. Not to be a Python
elitist, but is this how it is in Ruby? I'm new to the red world, and I'm a bit
surprised this is a problem; I never had an issue like this with Python virtualenv
pythons and system pythons.

_Update:_ Hours later I got the site to build from the system ruby by deleting
my Gemfile.lock. I don't even. It's just part of the learning process I suppose.
