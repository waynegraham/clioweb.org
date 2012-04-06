---
date: '2006-05-04 09:07:11'
layout: post
slug: css-based-timelines
status: publish
title: CSS-Based Timelines
wordpress_id: '364'
tags:
- Projects
---

Some of us at CHNM are trying to create a CSS/XHTML/JavaScript-based historical timeline, one that uses accessibile, semantic code but presents itself in graphically-complex ways and is portable across devices and programs. I haven't found any examples of this on the Internet, but I have found several examples of timelines in general.




Most sites display a timeline as tabular data or, more commonly, in plain, unsemantic HTML.






  * [Abraham Lincoln timeline](http://www.historyplace.com/lincoln/index.html)


  * [That Wacky Century!](http://pw2.netcom.com/~rogermw/century.html)


  * [Harriet Tubman timeline](http://www.math.buffalo.edu/~sww/0history/hwny-tubman.html)




In other cases, sites use an image created in Photoshop, Illustrator, or some other graphics program. While visually appealing, they're void of any hard-coded data pertaining to the events displayed. Examples include:






  * [Dickens Timeline](http://www.fidnet.com/~dap1955/dickens/swish_timeline/timeline_graphic.gif)


  * [Timeline of GNU/Linus and Unix](http://minnie.tuhs.org/TUHS/Images/unixtimeline.gif)


  * [Timeline of Philosophers](http://www.trincoll.edu/depts/phil/philo/timeline.html)




This, while the timeline in the first few examples actually contain coded data (even if that data is relatively meaningless), they aren't as complicated graphically as the images. Conversely, while the images convey some sense of change over time and multiple layers for events, the fact that they include no actual code pertaining to the events make them inaccessibile and unusable in other contexts. We want a semantically-coded list of events that we can make graphically stimulating and usable in a number of different settings.




Right now, the best option involves creating an XML file of the events and parse that XML with either Flash or with Scalable Vector Graphics (SVG), a relatively recent standard advocated by the World Wide Web Consortium (W3). Regarding the latter, the [Historical Event and Markup Linking Project](http://heml.org) (HEML) has produced a working XML schema that helps to, among other things, code and output an historical timeline. See, for example, the timeline of [Archaic Greece](http://heml.mta.ca/samples/blocks/heml/with_sidebar/with_browser/timelineRef.html?url=docs%2Fsource%2Fheml%2Farchaicgreece.xml&docType=file&fontName=Arial+Unicode+MS) or [Alexander the Great](http://heml.mta.ca/samples/blocks/heml/with_sidebar/with_browser/timelineRef.html?url=docs%2Fsource%2Fheml%2Falexander.xml&docType=file&fontName=Arial+Unicode+MS). While timelines may be the bane of some historians' existences (and the timelines presented at the HEML site are very simple), the challenge associated with coding and presenting a timeline really fascinates me. The Alexander timeline could easily be done with plain CSS and XHTML.  The Archaic Greece timeline, however, is a little more visually complex because events overlap each other and lines associated with certain places on the timeline structure the presentation of events. While the Alexander time is fairly linear, the Archic Greece timeline has more  layers, or "depth," for lack of a better term. Overlapping of events and associations among events present challenges to making digital timelines with plain HTML and CSS.




I'm confident that there's a solution, using dashes of CSS and JavaScript with a solidly-structured XML or XHTML page. If examples of this already exist, please send me links or examples. If not, feel free to leave you thoughts on this problem.
  *[XML]: Extensible Markup Language
  *[HEML]: Historical Event and Markup Linking Project
  *[SVG]: Scalable Vector Graphics
  *[CHNM]: the Center for History and New Media
  *[HTML]: Hypertext Markup Language
  *[W3]: World Wide Web Consortium
  *[XHTML]: Extensible Hypertext Markup Language
  *[CSS]: Cascading Style Sheets
