# Breakpoints

> Setting

The `wocss-settings-breakpoints` module contains breakpoints `variables` for the framework. Feel free to use these variables throughout your project, but be **careful** with modify or reassign them.

Install using npm:

```sh
$ npm install wocss-settings-breakpoints --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-settings-breakpoints';
```

### Variables list

| Variable name | Default value |
|---------------|-------|
| $breakpoint-xs | `320px` |
| $breakpoint-sm | `480px` |
| $breakpoint-md | `768px` |
| $breakpoint-lg | `992px` |
| $breakpoint-xl | `1200px` |
| $breakpoints  | `()` |
