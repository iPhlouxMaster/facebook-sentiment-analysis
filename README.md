facebook-sentiment-analysis
===========================

Facebook app written during HackMadison2014 event at UW-Madison. Analyses emotions between friends by collecting their interactions through messages, comments, etc.

How to use
==========

Make sure to turn off ghostery or similar apps to run this site. Also this app was poorly written, hence it will ask for too many permissions, please accept them for now or atleast the ones which you feel necessary after reading the description above. I will clean this.

Select a friend from the dropdown box and wait for the dial to become steady.

Result is on the scale of 0 to 1, 0 for most negative emotion, 1 for the best.

Utilities
=========

php, javascript, postgresql

Acknowledgements
================

Source code at <a href="https://github.com/kch/heroku-php-pg">https://github.com/kch/heroku-php-pg</a> helped in connecting to Heroku postgresql database.

Remarks
=======

1) Model used here to unify emotions assigned to each word from <a href="http://sentiwordnet.isti.cnr.it/">SentiWordNet3.0</a> is `not accurate` and more precisely it is `wrong`, which will be updated in future. For now consider this app as a fun project instead of taking results seriously.

2) This folder contains many scripts that are not being used for this project. Requires cleanup.

