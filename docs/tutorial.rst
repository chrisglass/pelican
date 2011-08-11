###########################
Tutorial: from zero to blog
###########################

This intends to take you from a fresh machine with nothing installed to a fully
working custom-themed blog using pelican.

This guide assumes you're using Ubuntu because that's what I use. You should
probably be able to make sense of theses instructions no matter what platform
you're on.

Step 0: Getting the required bits
#################################

First of all, you'll need a few things to get your blog running:

 #. Python. That's already installed for you! Jolly good!
 #. virtualenv. This lets you isolate your Python environments. Install it with
 ``sudo aptitude install python-virtualenv``

From there on, you have pretty much all you need to really get started! Let's
begin with the real stuff:

 * ``mkdir myblog``
 * ``cd myblog``
 * ``virtualenv --no-site-packages .``
 * ``source bin/activate``
 * ``pip install pelican``

 You can now follow the rest of this tutorial.

Step 1: Setup the structure
###########################

Our blog needs a few things to get started: a place to put our articles, a
theme, and a settings file to make it all work.

 * ``mkdir articles``. This is where your articles will reside.
 * ``mkdir myblog_theme``. We will get to this one up later.
