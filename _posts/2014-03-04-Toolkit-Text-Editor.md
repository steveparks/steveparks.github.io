---
layout: post
title: My Toolkit - Text Editor
categories: Geek
tags: Toolkit
---

Working on websites, and even writing the posts for this blog (in Markdown), means I need to use a good text editor.

The app I chose for this is the very popular [Sublime Text](http://www.sublimetext.com/).

## Sublime Text On The Command Line
If you work on the command line a lot, it's worth setting up aliases to make it possible to run Sublime Text from there. I run the two commands below which gives me the alias `subl` which is the default one that tends to be assumed, but I also prefer having `sublime` available as it's what I tend to think of.

    ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/sublime

    ln -s /Applications/Sublime\ Text\ 2.app/Contents/SharedSupport/bin/subl /usr/local/bin/subl

Tip via [Olivier Lacan](https://gist.github.com/olivierlacan/1195304).

## Sublime Text and Drupal
I work with Drupal alot, and so have needed to add a number of extensions, and set some configuration options to get the best experience.

To do this, the following pages are really useful:
- [Drupal.org page on Sublime Text](https://drupal.org/node/1346890)
- [Instructions for Config, including a bash script](http://www.phase2technology.com/blog/sublime-text-2-for-drupal-development/)
- My colleague Roel blogged about [setting up Codesniffer with Sublime Text](http://www.wunderkraut.com/blog/sublime-text-2-and-codesniffer-with-drupal-on-mac-osx-lion/2012-02-24)

## Summary
Sublime Text is very versatile, with a wide range of plugins available, and the ability to customise any part of the configuration. But it's also very simple, and it's that combination of the power to customise, with the simplicity out of the box, that makes it a winner.
