__WARNING: DO NOT POINT YOUR BUILDPACK CONFIG TO THIS PROJECT__

This buildpack is very specific to our needs, it can and will change and your app __WILL BREAK__.
Even the fonts in `fonts.tar.gz` are *probably not what you want or expect*.

We'd hate to see that happen to you. But please feel free to fork it or crib ideas to make it your own, though!

# Heroku Buildpack for Custom fonts

Fonts used by [ServeManager](https://www.servemanager.com) for printing documents.

## Development

### Create archive
```
tar -cvf fonts.tar *.ttf
```

### Inspiration
* https://github.com/debitoor/heroku-buildpack-converter-fonts
