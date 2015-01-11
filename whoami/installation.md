---
layout: page
title: WhoAmI Installation
original_url: http://whoami.opendfki.de/wiki/Installation
---

How to Install WhoAmI:

Be sure [Requirements](/whoami/requirements.html) are fulfilled before starting the installation.

### Install gems

You install the gems and soruce by downloading the installer Rakefile:

```
wget http://whoami.opendfki.de/repos/trunk/lib/tasks/install.rake rakefile
```

and run:

```
rake install:all
```

That's it!

The command installs these vendor gems:

  * feed-normalizer
  * rflick
  * youtube
  * twitter4r

As well as my individual gems taken from svn (​https://whoami.opendfki.de/repos/gems)

  * mylastfm
  * mydelicious
  * plazes

*optional:* to get everything ready for deployment, run:

```
rake install:deploy_gems
```

### Install source

To get WhoAmI run:

```
rake install:whoami
```

which basicly just runs: `svn co ​https://whoami.opendfki.de/repos/trunk whoami`

### Setup database

Set database values in `whoami/config/database.yml` and run migrate:

```
cd whoami
rake db:migrate
```

### Usage

Now everything is ready to run. Continue reading [WhoAmI Usage](/whoami/usage.html)
