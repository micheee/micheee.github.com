---
layout: post
title: "BaseX — XML Prague"
date: 2012-02-13 11:20
comments: true
author: Michael Seiferle
categories: BaseX XML Prague XQuery BaseX-Web
---


XML Prague 2012 is over. It has been a great, inspiring meetup, perfectly organized just as it was the year before.
We are currently on our way back home, so I took the chance to write a little wrap-up, especially for those who couldn't make it to Prague. 
But visitors of either the conference or our workshop are in particular invited to read on as well.

**Please note:** I’ll soon update this post with the slides we have shown. :-)

**February 15:** Rositsa’s slides on XQuery modules have been added. Dimitar’s slides on indexing have been added.
<!-- more -->

BaseX Preconference Day  ★ XML Prague 2012
-----------------------------------------

After attending eXist’s slick workshop last year, we decided to do a BaseX user meeting in 2012 as well.

We have been pretty busy preparing the Preconference Day thus we have been happy to see so many of our users there.
Actually we nearly did not make it to the venue as our car refused to start, thanks to Prague’s -20°C nights.

The schedule was tight and, hopefully, filled with interesting stuff.
After [Alex](http://twitter.com/holualex) introduced himself and our team, [Christian](http://twitter.com/christiangruen) gave an initial overview on [BaseX’](http://basex.org/) functionalities and features.

I myself provided a high-level look at the web architecture I’ve been working on recently.
The slides I made with <code>impress.js</code> can be found either on xquery-webapp-skeleton @ GitHub or you may as well have a [look at them](/images/static/basex-web-slides/app/page/index.html#/) here, without the need to clone anything.
These concepts have been superseded to some extent, as we opted to pursue [Adam’s](http://twitter.com/adamretter) approach of annotating RESTful endpoints directly in a controller.
But anyway, the key ideas of using solely XML-technologies applies here as well.

After an highly anticipated coffee break, Rosi equipped the audience with profound thoughts of our current XQuery module architecture, the EXPath repositories, and the built-in extension functions with: [Rositsa Shadura: XQuery Modules in BaseX](/images/XML-Prague-2012/BaseX-XQuery-Modules.pdf)

{% pullquote %}
The formal schedule was concluded with Dimitar’s talk, covering the “[The World of Indices](/images/XML-Prague-2012/indexes-basex-dimitar.pdf)” which was particularly interesting regarding chances and challenges of index updates.
{"Incremental updates are on their way."}
This led to some nice *Q&A* regarding Do’s and Dont’s, anyway it was general consent that incremental indices are highly wanted, by both our users and our team.
With the current release we added the <code>SET UPDINDEX on</code> option (see [BaseX Wiki] for more details) that enables incremental updates for the <code>TEXT</code> and <code>ATTRIBUTE</code> indices. 
We are confident that incremental updates to the full-text index will be added very soon.

{%endpullquote%}


Just before lunch-time the guys from [28msec](http://28msec.com/) took the stage and showed off their impressive cloud architecture. 

Pictures
--------
{% img  /images/XML-Prague-2012/Rosi.jpg 150 200 Rosis talk %}
{% img  /images/XML-Prague-2012/accomodation.jpg 200 150 Our hotel %}
{% img  /images/XML-Prague-2012/moldau.jpg 200 150 Vltava %}
{% img  /images/XML-Prague-2012/conference-dinner.jpg 150 200 Conference Dinner %}

Please make also sure to have a look at the [proceedings for XML Prague 2012](http://www.xmlprague.cz/2012/files/xmlprague-2012-proceedings.pdf "XML Prague Proceedings")

[BaseX Wiki]: http://docs.basex.org/wiki/Options#UPDINDEX [BaseX Documentation: Options]