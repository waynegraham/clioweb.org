---
date: '2005-06-20 12:45:23'
layout: post
slug: css-footnotes
status: publish
title: CSS Footnotes
wordpress_id: '118'
---

Paula's [CSS tutorial on footnotes](http://historytalk.typepad.com/basic/2005/06/introduction_by.html) has made me think of some other ways to implement footnotes using CSS. I've tried to streamline Paula's version by styling only the `<a>` by applying a class="note".  Instead of putting `<a>` inside `<span class="refnote">` (as Paula does)or `<sup>`, we can simply style the `<a>`. See the CSS below:


`
body {
	font-family: Verdana, sans-serif;
	font-size: 76%;
	color: #333;
	width: 800px;
	}
a.note {
	vertical-align:super;
	font-size: 0.8em;
	line-height:0;
	padding: 3px 5px;
	background-color: #ccc;
	color: #333;
	text-decoration:none;
	margin: 0 0.20em;
	}
a.note:hover {
	background-color: #ffc;
	color: #900;
	}
p {
	line-height: 2em;
	font-weight: 1em;
	}
`


[See the example](http://clioweb.org/workshop/endnotes/).




This seems to work fine on the following browsers: Windows - Opera 8, IE 6, Firefox; Mac - Safari, Firefox, IE5. Feel free to let me know if there are problems with other broswers.
