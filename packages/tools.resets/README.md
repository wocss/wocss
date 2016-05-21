# Resets

The `wocss-tools-resets` module contains a mixin that allows reset all the things.

Install using npm:

```sh
$ npm install --save wocss-tools-resets
```

## Usage

### reset-input()

Removes any styles that were previously set on a input.

```scss
.form-control {
  @include reset-input();
  // more code
}
```

### reset-list()

Removes any styles that were previously set on a list, clearing out all the margins and padding that are there by default.

```scss
.items {
  @include reset-list();
  // more code
}
```

### reset-link()

Removes any styles that were previously set on links, even that annoying text-decoration.

```scss
.article {
  @include reset-link();
  // more code
}
```

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.default)
