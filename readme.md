# Prototyping Boilerplate

I made this as a quick alternative to both browser based prototyping tools and setting up a build system every time you want to experiment.

It makes the assumption that you are using a modern browser which supports both ES Modules and CSS Custom Properties. If your prototype is a success, you can package those same modules using your build system of choice.

## Minimal Requirements

- Git
- Node and NPM
- `http-server` is the only NPM dependency.

## Get Started

- `$ git clone https://github.com/thoughtis/prototyping-boilerplate.git`
- `$ npm install`
- `$ npm run start` to serve locally using `http-server`

## Scripting

This boilerplate uses ECMAScript Modules in the browser. See [this post](https://jakearchibald.com/2017/es-modules-in-browsers/) on Jake Archibald's blog for more info on how to use them this way.

> Note: My example modules use strict mode in each module. This is a personal choice and may not be required.

## Styling

For consistency's sake, [normalize.css](https://github.com/necolas/normalize.css/) is included via CDN.

No magic here, just use custom properties if you need variables, and you can get them ready for production later.