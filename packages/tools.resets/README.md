# Resets

> Tool

The `wocss-tools-resets` module contains `mixins` that allows reset all the things.

Install using npm:

```sh
$ npm install wocss-tools-resets --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-tools-resets';
```

### Mixins

Then you can use these mixins:

#### reset-input()

Removes any styles that were previously set on a input.

```scss
.form-control {
  @include reset-input();
  // more code
}
```

#### reset-list()

Removes any styles that were previously set on a list, clearing out all the margins and padding that are there by default.

```scss
.items {
  @include reset-list();
  // more code
}
```

#### reset-link()

Removes any styles that were previously set on links, even that annoying text-decoration.

```scss
.article {
  @include reset-link();
  // more code
}
```
