# Wrapper

> Object

The `wocss-objects-wrapper` module contains the wrapper `object`, its like `container` [bootstrap class](http://getbootstrap.com/css/#overview-container).

Install using npm:

```sh
$ npm install wocss-objects-wrapper --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-objects-wrapper';
```

Then you can use the `o-wrapper` class for a responsive fixed width container:

```html
<div class="o-wrapper">
  <!-- here your content -->
</div>
```

## Dependencies

* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
* [wocss-tools-layout](https://github.com/wocss/tools.layout)
