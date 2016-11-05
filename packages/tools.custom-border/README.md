# CUSTOM-BORDER

> Tool

The `wocss-tools-custom-border` module contains `mixins` that allows you to add borders with customizable `width` and `height`.

Install using npm:

```sh
$ npm install wocss-tools-custom-border --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-tools-bem-constructor';
```

## Mixins

Then you can use these mixins:

### custom-border-right($height: 1.1em, $width: 1px, $spacing: $global-spacing-unit, $color: currentColor)

Add a custom border right

```scss
.element {
  @include custom-border-right(1em, 2px, .5em, #0074d9);
}
```

Result:

```css
.element {
  margin-right: 0.5em;
  padding-right: 0.5em;
  position: relative;
}

.element::after {
  background-color: #0074d9;
  content: '';
  display: block;
  height: 1em;
  left: 100%;
  position: absolute;
  top: 50%;
  transform: translateX(-50%);
  width: 2px;
}
```

### custom-border-bottom($height: 1px, $width: 90%, $spacing: $global-spacing-unit, $color: currentColor)

Add a custom border bottom

```scss
li {
  &:not(:last-child) {
    @include custom-border-bottom(2px, 2em, .5em, #0074d9);
  }
}
```

Result:

```css
li:not(:last-child) {
  margin-bottom: 0.5em;
  padding-bottom: 0.5em;
  position: relative;
}

li:not(:last-child)::after {
  background-color: #0074d9;
  content: '';
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  top: 100%;
  transform: translateY(-50%);
  width: 2em;
}
```

## Dependencies

* [wocss-settings-global](https://github.com/wocss/settings.global)
