# Hurry Asteroid

A RSS reader in a static webpage.

- Designed to be minimal and ephemeral-- items are shown only **once** and **disappear**
  on the next run.
- Everything is flat files. No database.
- Open in browser. No webserver needed

## Requirements

- [feedparser](https://feedparser.readthedocs.io)
- [dominate](https://github.com/Knio/dominate)

## Install

Drop hurryasteroid somewhere in your PATH

## Usage

add feed:

```
hurryasteroid add [title] [url]
```

build webpage (in current folder):

```
hurryasteroid
```

## Thanks

Asteroid image by Good Stuff No Nonsense [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 
