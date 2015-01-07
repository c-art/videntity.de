---
layout: post
status: publish
published: true
title: WhoAmI Features
author:
  display_name: tobi
  login: tobi
  email: t.bielohlawek@gmail.com
  url: http://
author_login: tobi
author_email: t.bielohlawek@gmail.com
author_url: http://
wordpress_id: 19
wordpress_url: http://www.videntity.de/2007/07/12/whoami-features/
date: '2007-07-12 15:31:19 +0200'
date_gmt: '2007-07-12 13:31:19 +0200'
categories:
- WhoAmI
tags: []
comments: []
---
Take this:

**WhoAmI** is a tool to aggregate your personal media shared on the internet. Everything what you share, your images, videos, bookmarks, music, blog posts etc. are merged into one place. The content is analyzed on keywords, permalinks and mapped to a simple ontology. If no tags are available the content is automatically tagged. Is a tag identified as location its geodata is added.

The resulting semantic relations are visualized via tagcloud, timeline, map or in detail. For further processing, your media can be accessed via RSS Feed or iCal (e.g. adding to your feed reader or calendar).

Primary access to the data is established trough the APIs of the web-services. Therefore your password or authorization has to be provided. If you feel uncomfy giving away your data, just provide your username. This falls back to public accessible RSS/Atom feeds. Although this doesn't give access to data of the past, your future content is processed as nearly good as content aggregated via API.

Features in summary:

  * support for multiple Web2.0 profiling accounts: Flickr, Youtube, Last.fm, Del.icio.us and Wordpress Blogs
  * analyzation on shared tags, permalinks
  * automatic tag retrieving of blog posts via tagthe.net
  * automatic (simple) geotagging of found plazes
  * Thumbnail preview
  * Detail view of relations, time, tags, plaze etc.
  * Timeline &amp; GeoTag visualization
  * Filter on time, tags and content type
  * RSS &amp; iCal access
  * Account data fallback to RSS/ATOM feed in case password/auth is not provided
  * see top relations
  * see clustered data
  * support for OpenID sign on
  * Controllable background workes for fetching content asynchronous
  * implemented with RubyOnRails
  * 100% RESTful
  * MySQL DB backend
  * OpenSource
  * Web 2.0 *- yeah!*

<img src='/images/screenshot.png' width='450' alt='whoami screenshot' />
