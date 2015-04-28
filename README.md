# Tantal Development Repository
An online math tool. Inspired by Wolfram Alpha this project aims to build a little website to made it easy solving math exercises on the computer.
Official site: https://p8h.github.io/tantal/

Website hosted on github in https://github.com/P8H/tantal

##Currently implementation status
Tantal includes following features
* Own vars
   * Assignment: n = 42;
   * Evaluation: n*2 = _v;
* Special vars
   * Value: _v(alue)
   * Previous formula: _b(efore)
* Standard math constants
   * Pi: pi
   * Euler: e
* Standard math functions
   * Summation: sum i over i from 0 to 10
   * Trigonometric functions: sin 2*pi


# Developing

This is a HTML5 application, built with [Brunch](http://brunch.io).

## Getting started
* Install (if you don't have them):
    * [Node.js](http://nodejs.org): `brew install node` on OS X
    * [Brunch](http://brunch.io): `npm install -g brunch`
    * [Bower](http://bower.io): `npm install -g bower`
    * Brunch plugins and Bower dependencies: `npm install & bower install`.
* Run:
    * `brunch watch --server` — watches the project with continuous rebuild. This will also launch HTTP server with [pushState](https://developer.mozilla.org/en-US/docs/Web/Guide/API/DOM/Manipulating_the_browser_history).
    * `brunch build --production` — builds minified project for production
* Develop:
    * `public/` dir is fully auto-generated and served by HTTP server.
    * Place static files you want to be copied from `app/assets/` to `public/`.
    * the main developing files are under `app/`

## Structure
Tantal based on the parser generator [PEG.js](http://pegjs.org).

## TODO
Tests.. with phantomjs? https://github.com/metaskills/mocha-phantomjs
