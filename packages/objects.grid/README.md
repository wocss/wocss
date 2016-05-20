# Cols

The `wocss-objects-cols` module contains cols object, a powerful grid system based on Flexbox.

Install using npm:

```sh
$ npm install --save wocss-objects-cols
```

**Note** The `cols object` use negative margins, you will need a root element overflowing the `cols object`, or it will cause horizontal scroll.

## Usage

### cols (object)

#### modifiers

* stretch
* middle
* gutter-# (replace # with a number 1 ~ 6)

### col (element)

#### modifiers

All modifiers may be prefixed with `@breakpoint` (replace breakpoint with xs, sm, md, lg, xl)

* auto
* fit
* `#` (replace # with a number 1 ~ 12)

```html
<div class="o-cols">
  <div class="o-cols__col"></div>
  <div class="o-cols__col"></div>
</div>
```

```html
<div class="o-cols o-cols--gutter-3">
  <div class="o-cols__col o-cols__col--12 o-cols__col--6@md"></div>
  <div class="o-cols__col o-cols__col--12 o-cols__col--6@md"></div>
  <div class="o-cols__col"></div>
</div>
```
