# Prototyping Boilerplate

This is a quick alternative to either browser based IDEs or setting up a build system every time you want to experiment.

It makes the assumption that you are using a modern browser which supports both ES Modules and CSS Custom Properties. If your prototype is a success, you can package those same modules using your build system of choice.

## Minimal Requirements

- Git
- HTTP server of choice

## Get Started

- `$ git clone https://github.com/douglas-johnson/prototyping-boilerplate.git your-project-name`

### Local Web Server

- Live Preview in VS Code works pefectly well.
- If you have [Python](https://docs.python.org/3/library/http.server.html#command-line-interface) or [PHP](https://www.php.net/manual/en/features.commandline.webserver.php) installed, you can use their built in HTTP server without installing anything else.
- Otherwise to serve locally using `local-web-server`
  - `npm install`
  - `npm run start`

## Scripting

This boilerplate uses ECMAScript Modules in the browser.

## Styling

No magic here, just use custom properties if you need variables, and you can get them ready for production later.
