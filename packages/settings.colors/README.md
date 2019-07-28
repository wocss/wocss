# COLORS

> Setting

The `@wocss/settings-colors` module contains basic, rainbow and RGBA colors `variables` for the framework. Feel free to use these variables throughout your project, but be **careful** with modify or reassign them.

Install using npm:

```sh
$ npm install @wocss/settings-colors --save
```

## Usage

With a tool like [webpack](https://webpack.github.io/) you can import this module writing:

```scss
@import '~@wocss/settings-colors';
```

### Variables

#### Basic colors

| Variable name | Default value |
|---------------|-------|
| `$black` | `#000000` |
| `$white` | `#ffffff` |

#### Rainbow colors

| Variable name | Default value |
|---------------|-------|
| `$silver` | `#dddddd` |
| `$gray` | `#aaaaaa` |
| `$navy` | `#001f3f` |
| `$blue` | `#0074d9` |
| `$aqua` | `#7fdbff` |
| `$teal` | `#39cccc` |
| `$olive` | `#3d9970` |
| `$green` | `#2ecc40` |
| `$lime` | `#01ff70` |
| `$yellow` | `#ffdc00` |
| `$orange` | `#ff851b` |
| `$red` | `#ff4136` |
| `$maroon` | `#85144b` |
| `$fuchsia` | `#f012be` |
| `$purple` | `#b10dc9` |

#### RGBA colors

| Variable name | Default value |
|---------------|-------|
| `$transparent` | `rgba(0, 0, 0, 0)` |
| `$full-black` | `rgba(0, 0, 0, 1)` |
| `$dark-black` | `rgba(0, 0, 0, 0.87)` |
| `$light-black` | `rgba(0, 0, 0, 0.54)` |
| `$min-black` | `rgba(0, 0, 0, 0.26)` |
| `$faint-black` | `rgba(0, 0, 0, 0.12)` |
| `$full-white` | `rgba(255, 255, 255, 1)` |
| `$dark-white` | `rgba(255, 255, 255, 0.87)` |
| `$light-white` | `rgba(255, 255, 255, 0.54)` |
| `$light-grey` | `rgba(239, 239, 239, 1)` |
| `$darken-1` | `rgba(0, 0, 0, 0.0625)` |
| `$darken-2` | `rgba(0, 0, 0, 0.125)` |
| `$darken-3` | `rgba(0, 0, 0, 0.25)` |
| `$darken-4` | `rgba(0, 0, 0, 0.5)` |
| `$lighten-1` | `rgba(255, 255, 255, 0.0625)` |
| `$lighten-2` | `rgba(255, 255, 255, 0.125)` |
| `$lighten-3` | `rgba(255, 255, 255, 0.25)` |
| `$lighten-4` | `rgba(255, 255, 255, 0.5)` |
