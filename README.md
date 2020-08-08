# About the News Feed Python

This is a set of scripts for aggregating RSS feeds.  It's based on
a script originally written by Dr. Drang:
<http://leancrew.com/all-this/2015/11/simpler-syndication/>
I'm not owner of code.

## Installation

Download all the files from this Gist.  Put them all in a directory, create a virtualenv and install requirements:

    ~/drangreader virtualenv env
    source env/bin/activate
    pip install -r requirements.txt

Put a list of feed URLs in `feeds.txt`.  One feed per line.  To create the HTML file:

    python main.py

Assuming nothing goes wrong, the posts will be written to `.html` file.

## What's next?
Try with Binder:
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/web-sys1/news-feed-python/master)

This notebook can also be run in the browser through binder.
