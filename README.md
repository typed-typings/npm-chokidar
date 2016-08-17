# Typed chokidar
[![Build Status](https://travis-ci.org/types/npm-chokidar.svg?branch=master)](https://travis-ci.org/types/npm-chokidar)

Typescript Typings for [chokidar](https://www.npmjs.com/package/chokidar).

## Installation
```sh
typings install --save chokidar
```

## Usage

```ts
read = gs.create('./files/**/*.coffee',  { /* options */ });

read.on('data', (file: gs.Element) => {
  console.log(file.path, file.base, file.cwd);
});

```


## Contributing
You can run them the tests with `npm run build` and `npm run test`.

--------------------------------

_Based on typings by [Stefan Steinhart](https://github.com/reppners/)_
