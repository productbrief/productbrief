---
layout: post
title:  "Tasker as Prototyping Tool"
author: ryan
categories: [ prototyping, tools ]
image: https://ryanhaber.s3.amazonaws.com/productbrief/content/images/neonbrand-618322-unsplash.jpg
featured: true
hidden: false
---

*tl;dr*: I used Tasker to pound together a quick and dirty interactive and functional prototype. You can, too. If you have an Android.

# My Bright Idea

Lately, I've been brainstorming problems and then the outlines of solutions. Some of the problems and their solutions are immense. Some of the problems are trivial and the solutions are really more for the shits and giggles.

Without going into too much detail at this point about the specific problem and solution, I'm going to try to explain how I used Tasker to put together, in a couple hours, a working prototype that I can now use to test my solution with potential customers. Well, really, I'm not so much testing the solution with them - but using the prototype to see if they even feel the problem enough to try to use my solution.

For now, suffice it to say that my solution is meant to facilitate quick and dirty communications among small groups. We'll just call my little project App X.

# Why Tasker? But First, What _Is_ Tasker?

[Tasker](https://play.google.com/store/apps/details?id=net.dinglisch.android.taskerm) is an Android-only app for using the inputs avaible to your phone as well as the outputs that it can manage and tying them each other using logic, flow control, variables, and the like. It's not really a language as much as a simple interface for making powerful scripts. Think [IFTTT](https://ifttt.com/discover) on steroids. Examples scripts I have used Tasker to do:

* Take a GPS snapshot of my location every five minutes and at the end of each day, export a CSV file of GPS coordinates to my Google Drive. I did this so I could make a satellite-cloud-type image of my daily movements.
* Sound an alarm if my phone is plugged in but not charging during nighttime hours (i.e., there's a power outage). I concocted this one before a hurricane came to town so that I could be alerted to a need to fire up my backup power generator to keep the sump pump running.
* Use a particular plug-in to create custom controls for Google Home so that I can do things like send SMS via Google Home voice commands.
* When I arrive within a geofence around my house for the first time in more than X minutes, text loved ones that I'm almost home.
* Sound a loud alarm when the phone receives an SMS with a designated code in it (to help me find it when lost).

You can find tons of other ideas out there.

In short, it's pretty powerful. It has tons of plugins available for letting you get weather conditions, load contact or calendar information into memory, and more. It even has some tools for making simple but effective and interactive UI elements.

Tasker is one of those apps that definitely has a nitch market. It appeals to tech nerds.

When I had my idea for App X, I thought, "What a pain - how much overhead there is just to get a prototype together to see if anyone even likes the idea or if I'm alone." As I was walking the dog, it dawned on me, that I could probably peel away a lot of the stuff that I know people enjoy, like chatting with friends. I could also peel away a lot of standard functionality that people expect, like syncing between mobile and web apps. And if I start with friends, I can peel away an impressive or fun UI. Those things peeled away, I realized that my idea is really simple. It's just a few steps, really.

And in a couple hours I'd put together a working prototype that actually does App X's cool, differentiating feature. It doesn't do it nice and pretty. But it does it.

And it's kinda fun to use.

Right now, some things are hardwired that can't be when I show it to friends. For instance, I hardwired my friends' contact information into the app.

I can use Tasker and its simple UI features to give friends an easy way to enter and store a few friends' details when they first run the app. Again, not full featured, but it will let them do the quick and dirty communication with their friends, rather than with mine.

Once I have this additional step in place, I think I'm good to start showing it off.