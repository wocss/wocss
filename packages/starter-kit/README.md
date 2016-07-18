# WOCSS Starter Kit

Install using npm:

```sh
$ npm install wocss-starter-kit --save
```

The `wocss-starter-kit` simply ties together a few key dependencies that are usually the starting point for any new project.

The `wocss-starter-kit` specifically contains some wocss default variables and mixins, as well as [Nicolas Gallagher](https://twitter.com/necolas)’s [Normalize.css](https://github.com/necolas/normalize.css) and global box-sizing rules.

With a tool like [webpack](https://webpack.github.io/) you can write:

```scss
@import '~wocss-settings-defaults';
@import '~wocss-settings-typography';

@import '~inuit-normalize';
@import '~inuit-reset';
@import '~inuit-box-sizing';
@import '~wocss-generic-shared';

@import '~wocss-base-defaults';
```

All modules have a `dependencies` section in their `README.md` file y las dependencias se instalaran junto al modulo, you don't need importing all the framework's modules.

## WOCSS (WTF)

This starts from a personal need, connect my variables with libs that i use, reuse mixins, easy way to starts new projects, these are my goals:

* use [bemit](http://csswizardry.com/2015/08/bemit-taking-the-bem-naming-convention-a-step-further/) naming convention.
* use [ITCSS](http://csswizardry.net/talks/2014/11/itcss-dafed.pdf) architecture.
* use [namespacing](http://csswizardry.com/2015/03/more-transparent-ui-code-with-namespaces/) classes.
* Share variables / mixins between libs like [basscss](basscss.com) and objects, components, etc.
