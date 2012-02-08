---
layout: post
title: "Mobile Apps &amp; Services"
date: 2010-05-05 01:29
comments: true
categories: [android, Facebook, GT, iUi, Jersey, MythTV]
---
I was looking through some files while cleaning up my computer and stubled upon some 
of the projects I did for Georgia Tech’s mobile applications and services class. 
The class consisted of three 3-week projects where groups worked to create mobile 
applications that involved some sort of information convergence on mobile platforms.

## Project 1: MobileMyth ##

This project created a mobile DVR solution for the popular PC DVR software MythTV. 
The project delivered a web based interface to the mobile phone using the iUi 
mobile web framework, which presents an IPhone-like interface no matter the mobile 
platform currently viewing the site. We linked this into MythTV to gather TVGuide 
data to display options to record and set recordings. We also linked Facebook using 
the Facebook Connect architecture which allows our application to make recommendations 
based on interests listed on user’s social profiles. We almost got streaming working 
(through several recompiles of ffmpeg), but it was left out of the final project because 
we couldn’t get it working cross-platform.

<iframe src="http://player.vimeo.com/video/11199913?title=0&amp;byline=0&amp;portrait=0" width="400" height="300" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe><p><a href="http://vimeo.com/11199913">Mobile Apps & Services: Project 3</a> from <a href="http://vimeo.com/therpaulsen">Ryan Paulsen</a> on <a href="http://vimeo.com">Vimeo</a>.</p>

## Project 2: GTLocate ##

This project was a wayfinding application for Georgia Tech on the android platform. 
We combined information from the campus map, Google Calendar, and Georgia Tech 
transportation data to show a heads up map showing where you are, where you need to be, 
and how to get there.

<iframe src="http://player.vimeo.com/video/11199802?title=0&amp;byline=0&amp;portrait=0" width="400" height="300" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe><p><a href="http://vimeo.com/11199802">Mobile Apps & Services: Project 1</a> from <a href="http://vimeo.com/therpaulsen">Ryan Paulsen</a> on <a href="http://vimeo.com">Vimeo</a>.</p>

## Project 3: ContextServer ##

Our second project was an extension of the GTLocate concept. The amount of data we needed to gather and display on the handset 
was too large for the handset to process efficiently (processor and network speed limitations). So, we decided to design a 
server component that aggregated and compressed data sources for processing by applications on a mobile phone. The server 
gathered data from multiple 3rd party sources and then compressed only the data needed into one smaller standardized XML or 
JSON transmission back to the phone. We made the system completely extensible using the Jersey framework for the REST operations 
and the Java Service Provider interface for handling new 3rd party data formats. We started with XML, Google Calendar, 
and ICal service providers, but any data format can be read into the system using that Service Provider interface. 
To demonstrate the system we adapted GTLocate to use the server to consolidate information.

<iframe src="http://player.vimeo.com/video/11199841?title=0&amp;byline=0&amp;portrait=0" width="400" height="300" frameborder="0" webkitAllowFullScreen mozallowfullscreen allowFullScreen></iframe><p><a href="http://vimeo.com/11199841">Mobile Apps & Services: Project 2</a> from <a href="http://vimeo.com/therpaulsen">Ryan Paulsen</a> on <a href="http://vimeo.com">Vimeo</a>.</p>