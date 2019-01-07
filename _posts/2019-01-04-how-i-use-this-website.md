---
title: How i use this website
author: Rohan Prasad
date: 2019-01-03
layout: post

---


This is both a test at uploading to the website, and a record for me of some things I should, and shouldn't do on it.

1. Do work on the gh-pages branch of this git repository (Website). Only then will it be processed by Github into a website.
2. Do use "git add -a", "git commit -m 'a message'", then "git push origin gh-pages". If some changes have been made online, use "git pull", resolve conflicts, and try again.
3. Do use "bundle exec jekyll serve" to test out the website locally.
4. Do *not* use "jekyll build", which would build the files into a real website format. Github does that for me. If I do it as well, Github gets upset and the website goes down.

Using layouts:

* The layout of a file is determined in the "front matter", which are words at the start of the file surround by three hyphens. In there, type "layout: post" (or whatever layout format I'm using).
* I'm planning to have a few different layouts:
	* home: the landing page of the website. Has a picture of me, and a short description of who I am (probably including a link to rohanprasad.org/resume)
	* thoughts: a layout that lists all the blog posts (written pieces) I've done, new to old. This is similar to the current "home" layout in minima (the default Jekyll theme).
	* doodles: similar to thoughts, but for art work. Displays a preview (somehow generated) of each doodle I've made, much like Instagram.
	* resume: a layout specifically designed for my resume. I can probably find something like this online.
	* post: pretty much exactly what "post" is in minima. In the future, this will possibly be different for doodles and thoughts. And will contain fancy footnotes in thoughts.

I also have to figure out the file structure for the pages, assets, and other things I include.
