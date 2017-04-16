# Constantinople
## A Pelican theme

A responsive theme for blogging and showcasing a portfolio and projects, powered by [Pelican](https://github.com/getpelican/pelican).

Constantinople began as a modified version of [atilla](https://github.com/arulrajnet/attila) by [@arulrajnet](https://github.com/arulrajnet). It is ported from the ghost theme [attila](https://github.com/zutrinken/attila) by [@zutrinken](https://github.com/zutrinken).

##Usage

**Adding Codepen.io display**

The following changes can be made in pelicanconf.py to enable the addition of Codepen.io pens. Pens can be embedded or displayed in a gallery with a short summary. 

For embedded pens, use the following
```python
CODEPEN = 'Your Codepen.io username'
EMBED_PENS = True
PEN_SHOWCASE = [
    {
        "embed" : 'The embed url from your codepen.io pen'
    }, {
        "embed" : 'The embed url from your codepen.io pen'
    }
    ]
```

For a pen gallery, use the following
```python
CODEPEN = 'Your Codepen.io username'
EMBED_PENS = False
PEN_SHOWCASE = [
    {
        "title" : "Magic 8 Ball",
        "slug" : "vXaoEj",
        "summary" : "A summary to display about the pen"
    }, {
        "title" : "Fun with Flexbox",
        "slug" : "VKaxBb",
        "summary" : "A summary to display about the pen"
    }
    ]
```
