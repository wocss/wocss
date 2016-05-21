# Media

The `wocss-objects-media` module contains the media object.

Install using npm:

```sh
$ npm install --save wocss-objects-media
```

## Usage

Basic usage of the Media object uses the required classes:

```html
<div class="o-media">
  <div class="o-media__left">
    <!-- here media content -->
  </div>
  <div class="o-media__body">
    <!-- here body -->
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
    <!-- here body -->
  </div>
</div>
```
