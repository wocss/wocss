# MEDIA

> Object

The `wocss-objects-media` module contains the media `object`.

Install using npm:

```sh
$ npm install wocss-objects-media --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-objects-media';
```

Then you can use the required classes:

```html
<div class="o-media">
  <div class="o-media__left">
    <!-- here media content -->
  </div>
  <div class="o-media__body">
    <!-- here body content -->
  </div>
</div>
```

### Modifiers

* `.o-media--gutter-[1|2|3|4]` alter the spacing between the elements.

### State

* `.is-reverse` reverse the horizontal rendered order of the left and body content.

For example:

```html
<div class="o-media o-media--gutter-2 is-reverse">
  <div class="o-media__left">
    <!-- here media content -->
  </div>
  <div class="o-media__body">
    <!-- here body content -->
  </div>
</div>
```

## Dependencies

* [wocss-settings-spaces](https://github.com/wocss/settings.spaces)
* [wocss-tools-bem-constructor](https://github.com/wocss/tools.bem-constructor)
