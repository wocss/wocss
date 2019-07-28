# TYPOGRAPHY

> Setting

The `@wocss/settings-typography` module contains font size and weight `variables` for the framework. Feel free to reassign these variables.

Install using npm:

```sh
$ npm install @wocss/settings-typography --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~@wocss/settings-typography';
```

### Variables

#### Font sizes

| Variable name | Default value |
|---------------|-------|
| `$global-fz-xl` | `1.5em` |
| `$global-fz-lg` | `1.25em` |
| `$global-fz-md` | `1.1em` |
| `$global-fz-sm` | `0.9em` |
| `$global-fz-xs` | `0.75em` |
| `$global-fz-h00` | `3rem` |
| `$global-fz-h0` | `2.4rem` |
| `$global-fz-h1` | `2rem` |
| `$global-fz-h2` | `1.5rem` |
| `$global-fz-h3` | `1.25rem` |
| `$global-fz-h4` | `1rem` |
| `$global-fz-h5` | `$global-fz-h4` |
| `$global-fz-h6` | `$globa-fz-h4` |
| `$wocss-font-sizes`  | `(...)` |

#### Font weights

| Variable name | Default value |
|---------------|-------|
| `$global-fw-x-bold` | `800` |
| `$global-fw-bold` | `700` |
| `$global-fw-s-bold` | `600` |
| `$global-fw-regular` | `400` |
| `$global-fw-light` | `300` |
| `$wocss-font-weights`  | `(...)` |
