# Typed chokidar
[![Build Status](https://travis-ci.org/types/npm-chokidar.svg?branch=master)](https://travis-ci.org/types/npm-chokidar)

Typescript Typings for [chokidar](https://www.npmjs.com/package/chokidar).

## Installation
```sh
typings install --save chokidar
```

## Usage

```ts
import * as chokidar from 'chokidar';

// One-liner for current directory, ignores .dotfiles
chokidar.watch('.', { ignored: /[\/\\]\./ }).on('all', (event: string, path: string) => {
  console.log(event, path);
});

```


## Contributing
You can run them the tests with `npm run build` and `npm run test`.

--------------------------------

_Based on typings by [Stefan Steinhart](https://github.com/reppners/)_
