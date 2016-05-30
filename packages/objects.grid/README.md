# Cols

The `wocss-objects-cols` module contains cols object, a powerful grid system based on Flexbox.

Install using npm:

```sh
$ npm install --save wocss-objects-cols
```

**Note** The `cols object` use negative margins, you will need a root element overflowing the `cols object`, or it will cause horizontal scroll.

## Usage

Basic usage of the Cols object uses the required classes:

```html
<div class="o-cols">
  <div class="o-cols__col"></div>
  <div class="o-cols__col"></div>
</div>
```

### Modifiers

#### cols

* `o-cols--stretch` columns with same height.
* `o-cols--middle` columns with vertical centering.
* `o-cols--gutter-[1|2|3|4|5|6]` alter spacing between columns.

#### col

All modifiers may be prefixed with `@[xs|sm|md|lg|xl]`.

* `o-cols__col--auto`
* `o-cols__col--fit` this column will take up the remaining space available.
* `o-cols__col--[1|2|3|...|12]` if you want to change the size of a single column, you can use one the following classes.

For example:

```html
<div class="o-cols o-cols--gutter-3">
  <div class="o-cols__col o-cols__col--12 o-cols__col--6@md"></div>
  <div class="o-cols__col o-cols__col--12 o-cols__col--6@md"></div>
  <div class="o-cols__col"></div>
</div>
```

### Breakpoints

| Key | Value |
|-----|-------|
| xs | `320px` |
| sm | `480px` |
| md | `768px` |
| lg | `992px` |
| xl | `1200px` |

### Gutters

| Key | Value |
|-----|-------|
| 1 | `.25rem` |
| 2 | `.5rem` |
| 3 | `1rem` |
| 4 | `2rem` |
| 5 | `4rem` |
| 6 | `8rem` |

## Dependencies

* [wocss-settings-defaults](https://github.com/wocss/settings.default)
* [wocss-tools-mixins](https://github.com/wocss/tools.mixins)
