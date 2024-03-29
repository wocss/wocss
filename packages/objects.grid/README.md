# GRID

> Object

The `@wocss/objects-grid` module contains the grid `object`, a powerful grid system based on Flexbox.

Install using npm:

```sh
$ npm install @wocss/objects-grid --save
```

**Note** The `grid object` use negative margins, you will need a root element overflowing the `grid object`, or it might cause horizontal scroll.

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~@wocss/objects-grid';
```

Basic usage of the Grid object uses the required classes:

```html
<div class="o-grid">
  <div class="o-grid__item"></div>
  <div class="o-grid__item"></div>
</div>
```

**Note** The `grid object` should be complemented with the [@wocss/utilities-widths](https://github.com/wocss/wocss/tree/master/packages/utilities.widths) module, for example:

```html
<div class="o-grid">
  <div class="o-grid__item u-12/12 u-6/12@tablet"></div>
  <div class="o-grid__item u-12/12 u-6/12@tablet"></div>
</div>
```

### Modifiers

#### `.o-grid`

* `o-grid--stretch` items with same height.
* `o-grid--middle` items with vertical centering.
* `o-grid--gutter-[1|2|3|4|5|6]` alter spacing between items, see [@wocss/spaces](https://github.com/wocss/wocss/tree/master/packages/settings.spaces#readme) variable.
* `o-grid--gutter-x-[1|2|3|4|5|6]` alter spacing between items on `x` axis, see [@wocss/spaces](https://github.com/wocss/wocss/tree/master/packages/settings.spaces#readme) variable.
* `o-grid--gutter-y-[1|2|3|4|5|6]` alter spacing between items on `y` axis, see [@wocss/spaces](https://github.com/wocss/wocss/tree/master/packages/settings.spaces#readme) variable.

#### `.o-grid__item`

* `o-grid__item--auto` the width of this item is based on its content width.
* `o-grid__item--fit` this item will take up the remaining space available. (modifier applied by default)

For example:

```html
<div class="o-grid o-grid--gutter-3">
  <div class="o-grid__item"></div>
  <div class="o-grid__item"></div>
  <div class="o-grid__item"></div>
</div>
```

## Dependencies

* [@wocss/settings-spaces](https://github.com/wocss/wocss/tree/master/packages/settings.spaces#readme)
* [@wocss/tools-bem-constructor](https://github.com/wocss/wocss/tree/master/packages/tools.bem-constructor#readme)
* [@wocss/tools-mq](https://github.com/wocss/wocss/tree/master/packages/tools.mq#readme)
