# Starter Kit

The `wocss-starter-kit` simply ties together a few key dependencies that are usually the starting point for any new project.

* [Global variables](https://github.com/wocss/settings.global)
* [Colors variables](https://github.com/wocss/settings.colors)
* [Typography variables](https://github.com/wocss/settings.typography)
* [Media queries mixins](https://github.com/sass-mq/sass-mq)
* [Bem constructor mixins](https://github.com/danielguillan/bem-constructor)
* [Sanitize.css](https://github.com/jonathantneal/sanitize.css)

Install using npm:

```sh
$ npm install wocss-starter-kit --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import all modules writing:

```scss
// SETTINGS
@import "~wocss-settings-global";
@import "~wocss-settings-colors";
@import "~wocss-settings-breakpoints";
@import "~wocss-settings-typography";

// TOOLS
@import '~wocss-tools-bem-constructor';
@import '~wocss-tools-mq';

// GENERIC
@import '~wocss-generic-sanitize';
```
