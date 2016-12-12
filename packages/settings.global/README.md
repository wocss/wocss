# GLOBAL

> Setting

The `wocss-settings-global` module contains settings that are available to your entire project. These variables and settings could be font families, colors, borders values, etc.

By default each variable in it, is required by some modules.

Install using npm:

```sh
$ npm install wocss-settings-global --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~wocss-settings-global';
```

### Variables

#### Colors

| Variable name | Default value |
|---------------|-------|
| `$global-color-primary` | `#7809ba` |
| `$global-color-secondary` | `#d4007c` |
| `$global-color-tertiary` | `#3a14be` |
| `$global-color-facebook` | `#3b5999` |
| `$global-color-twitter` | `#55acee` |
| `$global-color-google` | `#dc4e41` |
| `$global-color-youtube` | `#e52d27` |
| `$global-color-whatsapp` | `#43d854` |
| `$global-color-error` | `#cb5234` |
| `$global-color-warning` | `#edb431` |
| `$global-color-info` | `#3aa3e3` |
| `$global-color-success` | `#2ab27b` |

#### Borders

| Variable name | Default value |
|---------------|-------|
| `$global-border-radius` | `3px` |
| `$global-border-width` | `1px` |
| `$global-border-color` | `$global-color-primary` |

#### Others

| Variable name | Default value |
|---------------|-------|
| `$global-spacing-unit` | `1.5rem` |
| `$global-max-width` | `75rem` |
