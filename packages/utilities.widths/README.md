# WIDTHS

> Utility

The `wocss-utilities-widths` generates a series of utility classes that give a fluid width to whichever element they’re applied. These classes are most commonly used in conjunction with the [wocss-objects-grid](https://github.com/wocss/objects.grid) module,

Install using npm:

```sh
$ npm install wocss-utilities-widths --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-utilities-widths';
```

All classes might be suffixed with `@[mobile|tablet|laptop]` by default, see the [wocss-settings-breakpoints](https://github.com/wocss/settings.breakpoints).

e.g.:

```html
<div class="u-6/12 u-8/12@tablet"></div>
```
