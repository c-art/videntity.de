---
layout: page
title: WhoAmI
original_url: http://whoami.opendfki.de/wiki/Usage
---

## Running WhoAmI
If you've finished [Installation](/whoami/installation.html) continue reading:

## Start Server

To run WhoAmI, you have to start the included Webserver. This is done by running:

```
script/server
``

(It's okay just to click 'start server' when using out of-the-box-solutions like ​locomotive)

## Start Worker

In order to collect you contents, start the background worker server:

```
script/backgroundrb start
```

## Goto Website

Now you can surf to WhoAmI:

```
http://localhost:3000
```

To start a worker goto

```
http://localhost:3000/workers
```
