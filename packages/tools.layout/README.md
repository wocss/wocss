# LAYOUT

> Tool

The `wocss-tools-layout` module contains a few `mixins` to help tame those layouts.

Install using npm:

```sh
$ npm install wocss-tools-layout --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-tools-layout';
```

### Mixins

Then you can use these mixins:

#### layout-center($max-width: $global-max-width, $padding-x: $global-spacing-unit)

Center the element.

```scss
.container {
  @include layout-center(1000px, false);
}
```

Result:

```css
.container {
  display: block;
  margin-left: auto;
  margin-right: auto;
  max-width: 1000px;
  width: 100%;
}
```

#### layout-block($padding-x: $global-spacing-unit)

It makes an element a block.

```scss
.container {
  @include layout-block();
}
```

Result:

```css
.container {
  display: block;
  width: 100%;
  padding-left: 1.5rem;
  padding-right: 1.5rem;
}
```

## Dependencies

* [wocss-settings-global](https://github.com/wocss/settings.global)
