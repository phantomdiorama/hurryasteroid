# Hurry Asteroid

The difference between Hurry Asteroid and other, better feed readers is it shows only
the newest items and only once. No backlog can build up because items disappear on the
next run whether they've been read or not.

Other "features":

- No database. Everything is flat files.
- No webserver needed. Outputs a html file.

## Requirements

- [feedparser](https://feedparser.readthedocs.io)
- [dominate](https://github.com/Knio/dominate)

## Install

Install the above packages, then drop hurryasteroid somewhere in your PATH

## Usage

add feed:

```
hurryasteroid add [title] [url]
```

build webpage (in current folder):

```
hurryasteroid
```

**Note:** The output html is unstyled. However you can use your own css by adding style.rss
to folder with the html file. See `/extras` for an example.

## Thanks

- [Lorem RSS](http://lorem-rss.herokuapp.com/)
- Asteroid image by Good Stuff No Nonsense [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 
