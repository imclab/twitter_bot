INSTALLATION INSTRUCTIONS
=========================

Requirements
------------
Python 2.x
Python Twitter (see below)
SimpleJson
SimpleGeo's OAuth2
HTTPLib2 

SETTING UP
==========

Install Python Twitter
----------------------
Download the latest python-twitter library from:

  http://code.google.com/p/python-twitter/
  
Follow the instructions in the README

Get a Twitter Account
---------------------

Setup Credentials
-----------------
Create a file called credentials in the same directory as do_twitter.py
with the following format
Replace ??? with the values from your twitter account

    # Credentials from https://dev.twitter.com/apps/???/show

    consumer_key='???' 
    consumer_secret='???' 
    access_token_key='???' 
    access_token_secret='???'
  
Create a Data Directory and Files
---------------------------------
Edit the directory and file names in [common.py](https://github.com/peterwilliams97/twitter_bot/blob/master/common.py) 

Run [do_setup.py](https://github.com/peterwilliams97/twitter_bot/blob/master/do_setup.py) to create the data directory.

 

