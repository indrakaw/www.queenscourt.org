# www.queenscourt.org
An archive of The Queen's Court site. Keep it alive.

All downloads (zip, rar, etc) hosted in: https://googledrive.com/host/0B2nLo9e3GrameHBzYXc2QlJ3Tlk

## How to run locally
Make sure you have Ruby and RubyGems installed.

```BASH
git clone https://github.com/indrakaw/www.queenscourt.org.git
cd www.queenscourt.org
gem install bundler
bundle install
bundle exec jekyll serve
```

## Status
Status goes here.

## Conversation methods
All page in original site originally written in `.php`, and it archived-rebuild in `.html` static. See following methods:

General php pages with no `GET` url:
```
pagefilename.php
pagefilename.html
```
General php pages with `GET` url:
```
pagefilename.php?key=value
pagefilename/value.html
```

In this site there are 4 php with `GET` url:
```
/games.php?GameID=3
/games/3

/reviews.php?Game=Ara Fell
/reviews/ara fell

/misao/index.php?act=2005
/misao/2005

/screenshots.php?ImageID=12
screenshots/12
```

This site is hosted in [Netlify](//netlify.com) with `Pretty URLs` enable (ie. `/about.html` -> `/about`, `/about/index.html` -> `/about/`).

## Generated Site Structure
```
/
├── back.gif
├── banner.png
├── bishoujo.html
├── index.html
├── links.html
├── littlebullet.gif
├── othergames.html
├── games/
│   ├── 3.html
│   ├── 5.html
│   ├── 6.html
│   └── index.html
├── misao/
│   ├── 2002.html
│   ├── 2003.html
│   ├── 2004.html
│   ├── 2005.html
│   ├── 2006.html
│   ├── comm.html
│   └── index.html
├── reviews/
│   ├── ara fell.html
│   ├── index.html
│   ├── Iron Gaia.html
│   ├── Legend of the Philosopher's Stone.html
│   ├── Love and War.html
│   └── Naufragar.html
└── screenshots/
    ├── 12.html
    ├── 13.html
    ├── 14.html
    ├── 15.html
    ├── 17.html
    ├── 18.html
    ├── 19.html
    ├── 20.html
    └── 21.html
```

## Contribute

Feel free!

## Copyright

All contents is belong to their original authors.
**QueensCourt.org** is copyright to **iishenron**.

<!-- More copyright stuff goes here -->
