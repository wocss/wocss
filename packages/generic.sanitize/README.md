# Sanitize

> Generic

The `wocss-generic-sanitize` module contains a custom [sanitize.css](https://github.com/jonathantneal/sanitize.css).

Install using npm:

```sh
$ npm install wocss-generic-sanitize --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-generic-sanitize';
```

## Custom features

##### Images should be fluid for responsive purposes

```scss
img {
  font-style: italic;
  max-width: 100%;
}

img[width],
img[height] {
  max-width: none;
}
```
