
Twitter EMR
===========

Playing around with twitter data using Tweepy and BeautifulSoup. The idea is to figure out Amazon's [Elastic MapReduce](http://aws.amazon.com/elasticmapreduce/).


## Dependencies:

- [Tweepy](http://tweepy.github.io/)
- [BeatuifulSoup](http://www.crummy.com/software/BeautifulSoup/)


## Setup:

I'm using python [VirutalEnv](https://pypi.python.org/pypi/virtualenv) to manage my dependencies. You'll need a [twitter API key](https://dev.twitter.com/discussions/631).


## Runnning App

If using virutalenv, start environment first;

    $source bin/activate

Otherwise just run the main.py script;

    $python main.py
    
    
___

# Bugz

- Currently broken; I need to import an `app.config` file to load API credentials