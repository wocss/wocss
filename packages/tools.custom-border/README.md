# Custom border

> Tool

The `wocss-tools-custom-border` module contains `mixins` that allows you to add borders with customizable `width` and `height`.

Install using npm:

```sh
$ npm install wocss-tools-custom-border --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-tools-bem-constructor';
```

## Mixins

Then you can use these mixins:

### custom-border-right($height, $width, $spacing, $color)

Add a custom border right

```scss
li {
  &:not(:last-child) {
    @include custom-border-right(1em, 2px, .5em, #0074d9);
  }
}
```

### custom-border-bottom($height, $width, $spacing, $color)

Add a custom border bottom

```scss
li {
  &:not(:last-child) {
    @include custom-border-bottom(2px, 2em, .5em, #0074d9);
  }
}
```

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.defaults)
