# Prototyping Boilerplate

This is a quick alternative to either browser based IDEs or setting up a build system every time you want to experiment.

It makes the assumption that you are using a modern browser which supports both ES Modules and CSS Custom Properties. If your prototype is a success, you can package those same modules using your build system of choice.

## Minimal Requirements

- Git
- HTTP server of choice

## Get Started

- `$ git clone https://github.com/thoughtis/prototyping-boilerplate.git your-project-name`

### Local Web Server

- If you have PHP or Python installed, you can use their built in HTTP server without installing anything else.
- Otherwise
  - `npm install`
  - `npm install -g local-web-server` 
    * (`local-web-server` uses [`lws`](https://github.com/lwsjs/lws) cli and needs to be installed globally for cli command `ws` to be recognized)
  - `npm run start` to serve locally using `local-web-server`
  - `ws --help` for cli commands and settings
    * Additional CLI usage guide [HERE](https://github.com/lwsjs/local-web-server/wiki/CLI-usage)

## Scripting

This boilerplate uses ECMAScript Modules in the browser. See [this post](https://jakearchibald.com/2017/es-modules-in-browsers/) on Jake Archibald's blog for more info on how to use them this way.

> Note: My example modules use strict mode in each module. This is a personal choice and may not be required.

## Styling

No magic here, just use custom properties if you need variables, and you can get them ready for production later.