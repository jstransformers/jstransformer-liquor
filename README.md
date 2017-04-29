# jstransformer-liquor

[![Greenkeeper badge](https://badges.greenkeeper.io/jstransformers/jstransformer-liquor.svg)](https://greenkeeper.io/)

[Liquor](https://github.com/chjj/liquor) support for [JSTransformers](https://github.com/jstransformers).

[![Build Status](https://img.shields.io/travis/jstransformers/jstransformer-liquor/master.svg)](https://travis-ci.org/jstransformers/jstransformer-liquor)
[![Coverage Status](https://img.shields.io/codecov/c/github/jstransformers/jstransformer-liquor/master.svg)](https://codecov.io/gh/jstransformers/jstransformer-liquor)
[![Dependency Status](https://img.shields.io/david/jstransformers/jstransformer-liquor/master.svg)](http://david-dm.org/jstransformers/jstransformer-liquor)
[![NPM version](https://img.shields.io/npm/v/jstransformer-liquor.svg)](https://www.npmjs.org/package/jstransformer-liquor)

## Installation

    npm install jstransformer-liquor

## API

```js
var liquor = require('jstransformer')(require('jstransformer-liquor'));
var locals = {
  name: "World"
}

liquor.render('Hello, #{name}!', locals).body
//=> 'Hello, World!'
```

## License

MIT
