InstaBot
========

A simple Instagram bot that pulls trending top 100 hashtags and auto likes pictures with those hashtags to get more followers.

Developed in Python and built with the mechanize library

STILL IN DEVELOPMENT, CONTRIBUTIONS ARE WELCOME

##Requirements

1. Python is installed (Tested with version 2.6.8)
2. mechanize library is installed [Mechanize download!](http://wwwsearch.sourceforge.net/mechanize/download.html) V0.2.5
3. PyYAML libray is installed [PyYAML download!](pyyaml.org/wiki/PyYAML) V3.11
4. Authenticated your instagram account on [websta.me](http://websta.me/)

##Setup
Clone this repository:
```
git clone https://github.com/marclave/InstaBot.git
```

Modify the profile to include your information, example:
```
CREDENTIALS:
  USERNAME: username
  PASSWORD: cleverPassword
MAXLIKES: 1000 <- If you dont want a max, input NO_MAX
PERHASHTAG: 10 <- If you dont want a max, input NO_MAX
TOP: 1 <- To use the top hashtags on Websta.me use a 1 
```
Note: If you do not put a 1 in the value of TOP then the program will look for a text file
called hashtags.txt.

The format for this file is to have each hashtag seperated by line, example:

```
I
Love
Python
```

Then run:
```
python InstaBot.py
```
