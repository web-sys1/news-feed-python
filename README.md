# drangreader

This is a set of scripts for aggregating RSS feeds.  It's based on
a script originally written by Dr. Drang:
<http://leancrew.com/all-this/2015/11/simpler-syndication/>

## Installation

Download all the files from this Gist.  Put them all in a directory, create a virtualenv and install requirements:

    ~/drangreader virtualenv env
    source env/bin/activate
    pip install -r requirements.txt

Put a list of feed URLs in `feeds.txt`.  One feed per line.  To create the HTML file:

    python main.py

Assuming nothing goes wrong, the posts will be written to `output.html`.
