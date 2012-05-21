---
layout: post
title: "Backbone Podcatcher: Introduction"
date: 2012-05-20 14:55
comments: true
categories: Backbone Podcatcher
published: false
---

{% render_partial _partials/backbone-podcatcher-header.markdown %}

Who should read this?
--------------------
Well, to state the obvious: Anyone interested in developing applications with sinatra and backbone.js.
Moreover I am trying to make this as understandable as possible, so if you just learned Javascript and Ruby you should be able to follow it along.
There is a lot of material out there that covers introductory levels of Ruby, Javascript, Ruby on Rails, jQuery or Backbone.js.
This tutorial will pick up where most of these basic tutorials leave you.
Creating a non-trivial application is a different beast and can be intimidating, but I'll show you that it's not that hard.

What will be covered?
--------------------

  - The Vision: 
    If you're anything like me this is probably the most daunting part: You have a sea of possible features and interactions, yet you have to wittle them down to a combination of them that make a product. 
    There a several techniques to make it easier to envision the outcome of your development efforts.

  - The Model:
    I will try to answer what kind of data do you need and how do the individual pieces play together.
    This is another milestone towards understanding your application better and making the vision a bit more tangible.

  - The Architecture:
    The two major parts of this application are going to be a javascript-heavy client that communicates to the backend using a standardized API.
    We will see that having an API is not only useful when you want to expose it to other developers, but also make sense for internal use.
    
  - The Technology:
    This will contain a quick reasoning why I chose to use certain technologies, taking into account what we learnt so far about the application.

  - Prototyping the application:
    In this part we are going write a small proof of concept to check if the technologies that I chose playing nicely together.
    The last thing you want to do is finish one part of your application without knowing whether it will work with your other parts.

  - Getting a first version of the API:
    We'll start coding by converting the data model into a RESTful API using TDD.
    Never heard of REST? No worries, there's an introduction waiting for you and we'll look at several examples of RESTful APIs before designing ours.

  - Securing the API:
    
    


Why am I doing this?
-------------------
  - I've been thinking about this application for quite some time, so I would have written it even without this accompanying tutorial.

  - From my experience teaching software development to beginners I know that tutorials that target novice programmers but tackle hard problems are scarce.
    Just because you are not experienced does not mean that your 'software dreams' are smaller.

  - In part writing this tutorial is also an experiment: How hard is it to produce an accessible yet non-trivial tutorial?
    Does the reader gain more clarity from one consistent example that is explained from design to deployment?
    
  - Writing about a subject and explaining it so other people actually understand it requires and creates a much deeper level of understanding on the author's part.
    I have about three months worth of experience in javascript and this is my second application with backbone.js, so I am far from mastery.
    Bottom line is that I hopefully stand to gain just as much as any reader of this tutorial. 

One last disclaimer: I am writing this tutorial while I am developing the application, so I expect some dead ends.
Lesson 1: Software development is never smooth.


Similar tutorials
-----------------
  - [Building Backbone.js Apps With Ruby, Sinatra, MongoDB and Haml](http://addyosmani.com/blog/building-backbone-js-apps-with-ruby-sinatra-mongodb-and-haml/): Is a simpler application, does not cover the design stage or deployment.
  - [User Authentication with Rails and Backbone.js](http://42floors.com/blog/posts/user-authentication-with-rails-and-backbone-js) covers the authentication part in rails.

TODO
----
  - Use https://github.com/imathis/octopress/issues/544 for internal links

