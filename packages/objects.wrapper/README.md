# WRAPPER

> Object

The `wocss-objects-wrapper` module contains the wrapper `object`.

Install using npm:

```sh
$ npm install wocss-objects-wrapper --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-objects-wrapper';
```

Then you can use the `o-wrapper` class for a responsive fixed width container:

```html
<div class="o-wrapper">
  <!-- here your content -->
</div>
```

### Modifiers

* `.o-wrapper--[1|2|3|4]` alter the max-width.

## Dependencies

* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
* [wocss-tools-layout](https://github.com/wocss/tools.layout)
