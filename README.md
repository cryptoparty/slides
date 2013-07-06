slides
======

Description
-----------
an attempt to create a universal basic set of presentation slides to help teach basic conepts at Cryptoparties.

directory layout
----------------
We are trying to follow a convention to make navigation easier:
* slides/presentationXY/lang1

which looks like:

* slides/intro/en
* slides/intro/de

Producing slide shows with Pandoc
---------------------------------
cd /slides/intro/en/
pandoc -t slidy -s intro.md -o intro.html

cd /slides/otr/en/
pandoc -t slidy -s otr.md -o otr.html

* This produces an HTML + javascript slide presentation that can be viewed via a web browser.

* More information here http://johnmacfarlane.net/pandoc/README.html#producing-slide-shows-with-pandoc
