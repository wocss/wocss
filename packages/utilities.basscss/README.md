# BASSCSS

> Utility

The `@wocss/utilities-basscss` module contains a port of  [BassCSS](https://github.com/basscss/basscss/#basscss) library using `wocss` variables and the [BEMIT](http://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/) naming convention.

Install using npm:

```sh
$ npm install @wocss/utilities-basscss --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import all modules writing:

```scss
@import '~@wocss/utilities-basscss';
```

or import only that you need:

```scss
@import '~@wocss/utilities-basscss/src/utilities.hide';
@import '~@wocss/utilities-basscss/src/utilities.show';
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

  **NOTE**: There is not `max-width` utilities. (check [@wocss/objects-wrapper](https://github.com/wocss/wocss/tree/master/packages/objects.wrapper#readme))

* #### [Margin](http://www.basscss.com/#basscss-margin)

* #### [Padding](http://www.basscss.com/#basscss-padding)

* #### [Positions](http://www.basscss.com/#basscss-position)

* #### Show
  Use these utilities to conditionally show elements based on viewport width.

* #### [Type scale](http://www.basscss.com/#basscss-type-scale)

  **NOTE**: The `font-size` utilities has a extra namespace (`'fz'`). e.g.: `.u-fz-h1`

* #### [Typography](http://www.basscss.com/#basscss-typography)

  **NOTE**: The `font-weight` utilities has a extra namespace (`'fw'`). e.g.: `.u-fw-regular`

## Dependencies

* [@wocss/settings-global](https://github.com/wocss/wocss/tree/master/packages/settings.global#readme)
* [@wocss/settings-typography](https://github.com/wocss/wocss/tree/master/packages/settings.typography#readme)
* [@wocss/settings-spaces](https://github.com/wocss/wocss/tree/master/packages/settings.spaces#readme)
* [@wocss/settings-colors](https://github.com/wocss/wocss/tree/master/packages/settings.colors#readme)
* [@wocss/tools-bem-constructor](https://github.com/wocss/wocss/tree/master/packages/tools.bem-constructor#readme)
* [@wocss/tools-mq](https://github.com/wocss/wocss/tree/master/packages/tools.mq#readme)
* [@wocss/tools-resets](https://github.com/wocss/wocss/tree/master/packages/tools.resets#readme)
