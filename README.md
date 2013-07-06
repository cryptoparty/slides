# CryptoParty Slides

## Description

An attempt to create a universal basic set of presentation slides to help teach basic conepts at Cryptoparties.

## Layout

We are trying to follow a convention to make navigation easier:

    slides/<topic>/<language>

## Producing slide shows with Pandoc

```bash
$ cd /slides/intro/en/
$ pandoc -t slidy -s intro.md -o intro.html
$ cd /slides/otr/en/
$ pandoc -t slidy -s otr.md -o otr.html
$ cd /slides/risk/en/
$ pandoc -t slidy -s risk.md -o risk.html
```

This produces an HTML + javascript slide presentation that can be viewed via a web browser.

More information here [http://johnmacfarlane.net/pandoc/README.html#producing-slide-shows-with-pandoc](http://johnmacfarlane.net/pandoc/README.html#producing-slide-shows-with-pandoc)
