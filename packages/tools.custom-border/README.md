# Custom border

The `wocss-tools-custom-border` module contains a mixin that allows you to add borders with customizable `width` and `height`.

Install using npm:

```sh
$ npm install --save wocss-tools-custom-border
```

## Usage

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
