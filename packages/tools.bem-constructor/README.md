# Bem constructor

> Tool

The `wocss-tools-bem-constructor` module contains `mixins` to help tame those bem structures.

This is a modified version of [bem-constructor](https://github.com/danielguillan/bem-constructor), the selector ` >` was removed from `modifies-element` mixin, but you can reassign it, changing `$bem-modifies-element-separator` variable to `'>'`.

Install using npm:

```sh
$ npm install wocss-tools-bem-constructor --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
// dependencies imports

@import '~wocss-tools-bem-constructor';
```

### [Mixins doc](https://github.com/danielguillan/bem-constructor#blockname-type)
