---
layout: post
title: "Automate Instapaper for Nook (or any ebook reader)"
date: 2012-05-24 13:05
comments: true
category: instapaper_download
---
Yes, I know I know.
[Instapaper](http://www.instapaper.com) made reading so much more awesome, so awesome that I have premium subscription for no real reason.
Really, being able to dowload an ebook with all your unread articles is amazing, and here's the but: 
But everytime I am finished with a batch of articles I need to hook up my nook to my computer, go to the instapaper website, download the epub and then drag the file on my nook.

![First world problems](http://i.qkme.me/3pfbna.jpg)

Well, first world problems want to be solved too:
I created a gem that comes with a binary, so fire up your terminals, do a `gem install instapaper_download && instapaper_download`.
I am kind of embarrassed since it neither has tests nor accepts commandline parameters;
The former because I felt lazy, the latter because I want to streamline the process as much as possible.

When you start the application first it will ask you for your instapaper username and password, you can elect to save these credentials into a configuration file so the next time around it will run automatically (the whole point of this exercise).
Then it will download the epub file from you instapaper account and ask you where your ebook reader is mounted.
Again, this is only the first time around, you can choose to save it in the same configuration file.

The software is not super stable, I can say that the "happy path" works for me.
As already mentioned, I haven't done too much testing, but hey - shipping is a feature!
If you experience any problems, [open a new issue or send me a pull request](https://github.com/sebastiangeiger/instapaper_download).

#TODO: http://www.macresearch.org/tutorial_backups_with_launchd
