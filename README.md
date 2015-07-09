# Software Galaxies

This repository combines visualizations of major software package managers.
This is supposed to be shown at http://2015.cascadiajs.com/browser/

The slides are available here: http://anvaka.github.io/talks/cascadia2015/#/

I'm keeping it open, since I don't believe people care too much about what I'm
doing, but if you want to provide feedback - please do so.

# Visualizations

Each graph is indexed individually, and data is pushed to `gh-pages` branch
of [galactic-data](https://github.com/anvaka/galactic-data).

## Bower

* Indexed by [allbower](https://github.com/anvaka/allbower)
* [Live demo](http://anvaka.github.io/pm/#/galaxy/bower?l=1)

## PHP Composer

* Indexed by [allcomposer](https://github.com/anvaka/allcomposer)
* [Live demo](http://anvaka.github.io/pm/#/galaxy/composer?l=1)

## Ruby gems

* Indexed by [allgems](https://github.com/anvaka/allgems)
* [Live demo](http://anvaka.github.io/pm/#/galaxy/rubygems?l=1)

## npm

* Indexed by [allnpm](https://github.com/anvaka/allnpm)
* [Live demo](http://anvaka.github.io/pm/#/galaxy/npm?l=1)

## npm

* Indexed by [allgo](https://github.com/anvaka/allgo)
* [Live demo](http://anvaka.github.io/pm/#/galaxy/gosearch?l=1)

# local development

```
git clone https://github.com/anvaka/pm
npm i
npm start
```

## Data format

Binary graph format is described in the [ngraph.tobinary](https://github.com/anvaka/ngraph.tobinary#ngraphtobinary)

## Layout

Most of these graphs are using [ngraph.offline.layout](https://github.com/anvaka/ngraph.offline.layout)

The secret GitHub visualization is using [ngraph.native](https://github.com/anvaka/ngraph.native).
A force based layout rewritten in C++ (just because it's much faster).
