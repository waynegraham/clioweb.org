---
date: '2009-01-12 00:18:47'
layout: post
slug: new-and-updated-wordpress-plugins
status: publish
title: New (and Updated) WordPress Plugins
wordpress_id: '603'
tags:
- Courseware
- plugins
- Projects
- ScholarPress
- WordPress
---

I spent a little time this weekend updating some plugins I've had in the hopper. First, [Zac Gordon](http://zgordon.org/) and I updated [ScholarPress Courseware](http://wordpress.org/extend/plugins/scholarpress-courseware/) to work with WordPress 2.7. Many thanks to Zac for helping to update Courseware's interface elements to match 2.7's admin theme, and for adding an easy date picker to the schedule edit form. There are still some inconsistencies in the plugin between WP 2.6 and 2.7, but we did the best we could. We'll continue to make improvements to Courseware, so stay tuned at [ScholarPress](http://scholarpress.net).




I also cleaned up a few custom plugins that I've used on ClioWeb and various other sites. These two plugins, CW Author Base and CW Page Categories, do some simple stuff, but they've been handy to me, so I'm sharing them here in hopes that they're useful to someone else.






  * [CW Author Base](/downloads/cw_authorbase.txt)--This is a really simple plugin that lets you change the base for author URLs in WordPress. You can already do this for categories and tags in WordPress under the Settings tab, but not author URLs. I think this should be part of the core, but its not. So, if you wanna change the author URL base, save this file as a .php


  * [CW Page Categories](/downloads/cw_pagecategories.txt)--Another very simple plugin that lets you add categories to a page. It includes a template function called `cw_listcategories()` that you can use in the sidebar to list pages under a category heading. You can also return an array of pages with `cw_getpagesbycat($cat)` and replace `$cat` with the category ID.




As always, if you have suggestions for improvement, or add you own code to these plugins, please share!
