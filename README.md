# Readium 3

## Official Description

**The (the good parts) Medium-like theme for [Ghost](https://github.com/TryGhost)**. I took the good parts of Medium to bring you a similar reading and blogging experience while giving you the freedom to host your content on your own servers and on your own terms. In contrast to the previous version of Readium this one isn't a copy of Medium any more. Readium 3.0 sets out to be different than Medium (I have read so many Medium articles, that I can't stand them any more), while keeping what is good and building upon it. Readium now has it's own charm. It will always be somewhat similar (hopyfully better!), but never again will it be the same.

**Check out [my blog](http://normanew.com) as an example**.

If you give your images an alt text, it gets added automatically as figcaption beneath the image (sorry, no links or other HTML stuff).

## Software Requirements
- [Ghost] (https://github.com/TryGhost)

## Getting Started
1. You would need to clone this github repo `git clone git@github.com:normanew/readium.git` into your Ghost themes folder
2. Change your theme from the general settings of Ghost

## Required Configurations
1. There are Twitter Metadata that you would need to change
2. If you need to use the Google Analytics, please change the ID correspodingly.

## Features
- Mobile-First Design Approach
- Fully Responsive layout
- Use header images in articles
- Automatic figcaption generation from image alt tags
- Valid HTML5/CSS3
- WAI-ARIA & Rich Snippets(microdata) roles
- Minimal design
- Compatible up from Ghost 0.6
- Designed for Readability & Sharability
- Works with the Ghost Hosting platform
- Static pages welcome
- Featured article support
- FontAwesome implemented for easy use of icons fonts
- Highlight.js integrated for Syntax highlighting - [Highlight JS](http://highlightjs.org)
- OpenGraph & Twitter Cards meta's
- Free & Open Source Font usage

### Good to know

#### Half Images

While writing your article you decide it would be nice if the image wouldn't be full width. Half would be enough, text flowing around it. Well, we got you covered. Just surround your image with the following HTML code while writing inside the editor:
```
	<div class="image-left">
		![First load of beverages getting shipped to our location.](/content/images/2014/Jul/2014-07-11-11-45-01.jpg)
	</div>
```
A DIV with the class "image-left" makes your image float left and only take up 50% of the space. Same goes btw for "image-right" as well :).

## Modifications from Readium 3

I removed the pitch part since I didn't need it at my blog. Changes was also made to the Google Analytics tracking ID.

#### Thanks go to...
- [Readium 3](https://github.com/starburst1977/readium "Readium Github") by Sven Read
- FontAwesome by Dave Gandy
- Highlight JS by Ivan Sagalaev
- The awesome guys that make Ghost
- The really rad guys that design Medium


