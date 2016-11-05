# RESETS

> Tool

The `wocss-tools-resets` module contains `mixins` that allows reset styles.

Install using npm:

```sh
$ npm install wocss-tools-resets --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-tools-resets';
```

### Mixins

Then you can use these mixins:

#### reset-list()

Removes any styles that were previously set on a list, clearing out all the margins and padding that are there by default.

```scss
.items {
  @include reset-list();
}
```

Result:

```css
.items {
  list-style: none;
  margin-bottom: 0;
  margin-top: 0;
  padding-left: 0;
}
```
