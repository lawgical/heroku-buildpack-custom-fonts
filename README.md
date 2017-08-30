__WARNING: DO NOT POINT YOUR BUILDPACK CONFIG TO THIS PROJECT__

This buildpack is very specific to our needs, it can and will change and your app __WILL BREAK__.
Feel free to take fork or take ideas from it, though!

# Heroku Buildpack for Custom fonts

Fonts used by [ServeManager](https://www.servemanager.com) for printing documents.

## Development

### Create archive
```
tar -cvf fonts.tar *.ttf
```

### Inspiration
* https://github.com/debitoor/heroku-buildpack-converter-fonts
