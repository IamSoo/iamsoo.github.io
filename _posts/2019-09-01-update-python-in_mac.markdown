---
layout: post
title: Update Python version in Mac
date: 2019-09-01 14:00:20 +0300
description: How to update python version in mac
#img: pylogo.png # Add image post (optional)
fig-caption: # Add figcaption (optional)
---

Mac comes with default python version of 2.7. If we want to update the python version we need to install python3.
Either by manual installation by downloading the latest .pkg file from https://www.python.org/downloads/ or use homebrew.
To use homebrew follow the below steps:
* brew install python3

Once installed you can type python3 --version to verify the installation.
But still default python command will pickup python2.7.

To correct that we can alias the python to point python3 installation folder :
```
vi ~./bash_profile
alias python='/usr/local/bin/python3'
```
esc + :wq (save and exit)

Once we do that we can verify our new python version :
```
$ python --version
Python 3.7.4
```

