# wocss

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

Personal sass modules collection "inspired" by inuitcss

## Project setup
```
npm install
lerna bootstrap
```

## Development

### Commit your changes using [commitizen](https://github.com/commitizen/cz-cli)
```
npm run commit
```

## Troubleshooting

### Commit without validation
```
git commit -m "..." --no-verify
```

### Commit message format
```
feat(elements-table): add hat wobble
^--^ ^------------^   ^------------^
|    |                |
|    |                +-> Summary in present tense.
|    +------------------> Scope: folder name of package in kebab-case (e.g. elements-table)
|
+-----------------------> Type: chore, docs, feat, fix, refactor, style, or test.
```
