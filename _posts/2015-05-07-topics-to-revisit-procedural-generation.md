---
layout:     post
title:      "<i>Topics to Revisit:</i><br/>Procedural Generation"
date:       2015-05-07 21:00:00
categories: 
tags:       [Revisit]
published:  True
---

Procedural generation is a very broad topic, ranging from generating everything from levels, graphics, quests, music and more. Games like _Spore_ and _No Man's Sky_ and the demo scene take these concepts to extremes in spetacular fashion.


### Resources

A gentle introduction to procedural generation is [cantor city](http://procworld.blogspot.dk/2014/11/cantor-city.html) (see below) that makes a very simple cityscape.

![desk](http://2.bp.blogspot.com/-4DXBmMcQ7kE/VGfaKyPjzII/AAAAAAAAHJU/xIgDhW_ihFo/s1600/GrammarPreview%2B2014-11-14%2B17-05-42-77.gif)

For a more detailed, academic, coverage of various topics in procedural generation see Ian Parberry awesome [Procedural Content Generation](http://larc.unt.edu/ian/research/content/) resources page.

_Lennas Inception_, a game that draws inspiration from _Zelda_ and _The Binding of Isaac_, has a lot of [good resources](http://bytten-studio.com/devlog//tags.html#proceduralgeneration-ref) about practical procedurally generating 2D levels.

Much procedural content starts from simple noise functions. The always inspiring [Red Blob Games](http://www.redblobgames.com) has a [good introductory article](http://www.redblobgames.com/articles/noise/introduction.html) & [demonstration](http://www.redblobgames.com/articles/noise/2d/) of noise generation.

There's a great talk from GDC 2015 entitled [Making Things Up: The Power and Peril of PCG](http://www.gdcvault.com/play/1022134/Making-Things-Up-The-Power) that gives a broad overview of procedural generation and where it can be applied. On of the resources that is mentioned in the talk is the [Procedural Content Generation in Games](http://pcgbook.com/) book, which can be read freely online. Another good resource is the [Procedural Content Generation Wiki](http://pcg.wikidot.com/).

### My work

I have made an implementation of [Perlin Noise](http://en.wikipedia.org/wiki/Perlin_noise) in Haxe. It can be run from [here](http://try.haxe.org/#f1cc2), which will produce the following 2D noise:

![perlin noise]({{ site.baseurl }}/images/gamedev_topics/hx_noise.png)

The code is also [available as a gist](https://gist.github.com/anissen/fae4fa40a41e08430ae2):

{% gist fae4fa40a41e08430ae2 %}


### Ideas for revisiting

Use procedural generation for:

* Auto-generating quests and story
* Creating a dynamic soundtrack that reacts to in-game events
* Using text-to-speech (e.g. the Web Audio Speech Synthesis API) to create speech dynamically
* Boost replayability by generating levels and terrain
* Create new enemies and encounters from a database of prototypes

