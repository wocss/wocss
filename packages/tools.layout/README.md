# Layout

> Tool

The `wocss-tools-layout` module contains a few `mixins` to help tame those layouts.

Install using npm:

```sh
$ npm install wocss-tools-layout --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-tools-layout';
```

### Mixins

Then you can use these mixins:

#### layout-center($max-width, $padding-x)

Center the element.

```scss
.container {
  @include layout-center(1000px, 0);
}
```

#### layout-block()

It makes an element a block.

```scss
.container {
  @include layout-block();
}
```

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.defaults)
