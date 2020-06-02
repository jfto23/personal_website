---
layout: page
title: projects
---

## zlibtui

_zlibtui_ is a terminal UI for Z-library.

__[Source code](https://github.com/jfto23/zlibtui)__

![](/assets/images/zlibtui_pic.png)

The app was written with Python using
[blessed](https://pypi.org/project/blessed/) which is a wrapper for curses.
I used PyTest for testing the features. The project is 
deployed on PyPI. You can view the PyPI page [here](https://pypi.org/project/zlibtui/).

## mytype

_mytype_ is an online typing game
inspired by
the popular website [Typeracer](https://typeracer.com). 

__[Source
code](https://github.com/jfto23/mytype)__ | __[Live
version](https://serene-dawn-01436.herokuapp.com)__

![](/assets/images/mytype_pic.png)

The website uses a mySQL database hosted on JawsDB for storing the texts and
their respective top scores. The backend was built with NodeJS and ExpressJS. I used VueJS for
the frontend. The web app is deployed on Heroku.

There are currently 1000 texts available. Each text is taken directly from
Typeracer through their [database](http://typeracerdata.com/texts). For storage
reasons, only the top three scores are saved.

## superscheduler

_superscheduler_ is an online schedule builder.

__[Source code](https://github.com/jfto23/superscheduler/)__ | __[Live
version](https://jfto23.github.io/superscheduler/)__

![](/assets/images/superscheduler.png)

The app was made with VueJS and uses local storage to save the schedule and the
options. 
