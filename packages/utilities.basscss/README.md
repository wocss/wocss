# UTILITIES

> Trump

The `wocss-trumps-utilities` module contains a series of utilities classes, like [Basscss](http://www.basscss.com/) modules, but using `wocss` variables.

Install using npm:

```sh
$ npm install wocss-trumps-utilities --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import all modules writing:

```scss
@import '~wocss-trumps-utilities';
```

or import only that you need:

```scss
@import '~wocss-trumps-utilities/src/trumps.hide';
```

### Modules

* #### [Align](http://basscss.com/#basscss-align)

* #### [Background colors](https://github.com/basscss/addons/tree/master/modules/background-colors)

  **NOTE**: Here we have extra utilities classes. e.g.: `u-bg-primary`

* #### [Borders](http://www.basscss.com/#basscss-border)

* #### [Colors](https://github.com/basscss/addons/blob/master/modules/colors)

  **NOTE**: Here we have extra utilities classes. e.g.: `u-color-primary`

* #### [Flexbox](http://basscss.com/#basscss-flexbox)

  **NOTE**: There is a `u-flex-fit` (it can shrink to 0 width) and `u-flex-auto` (it can shrink to content width)

* #### [Hide](http://basscss.com/#basscss-hide)

* #### [Layout](http://www.basscss.com/#basscss-layout)

  There is not `max-width` utilities. (check [wocss-objects-wrapper](https://github.com/wocss/objects.wrapper))

* #### [Margin](http://www.basscss.com/#basscss-margin)

* #### [Padding](http://www.basscss.com/#basscss-padding)

* #### [Positions](http://www.basscss.com/#basscss-position)

* #### Show
  Use these utilities to conditionally show elements based on viewport width.

* #### [Type scale](http://www.basscss.com/#basscss-type-scale)

  **NOTE**: The `font-size` utilities has namespace ('fz'). e.g.: `.u-fz-h1`

* #### [Typography](http://www.basscss.com/#basscss-typography)

  **NOTE**: The `font-weight` utilities has namespace ('fw'). e.g.: `.u-fw-regular`

## Dependencies

* [wocss-settings-global](https://github.com/wocss/settings.global)
* [wocss-settings-typography](https://github.com/wocss/settings.typography)
* [wocss-settings-spaces](https://github.com/wocss/settings.spaces)
* [wocss-settings-colors](https://github.com/wocss/settings.colors)
* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
* [wocss-tools-mq](https://github.com/wocss/tools.mq)
* [wocss-tools-resets](https://github.com/wocss/tools.resets)
