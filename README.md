Placard API
===========

A simple [placard](https://www.jogossantacasa.pt/web/Placard) API client library for [node.js](http://nodejs.org).

[![npm version](https://badge.fury.io/js/placard-api.svg)](https://www.npmjs.com/package/placard-api)
[![Build Status](https://travis-ci.org/efernandesng/placard-api.svg?branch=master)](https://travis-ci.org/efernandesng/placard-api)
[![Coverage Status](https://coveralls.io/repos/github/efernandesng/placard-api/badge.svg?branch=master)](https://coveralls.io/github/efernandesng/placard-api?branch=master)

## Installation

```bash
$ npm install placard-api
```

## Example

```javascript
const placard = require('placard-api');

placard.nextEvents((err, data)=> {
    console.log(data)
})

// or

placard.nextEvents().then((data)=> {
    console.log(data)
})
```

## Documentation

- **faq([callback]) -> Promise**
- **fullSportsBook([callback]) -> Promise**
- **info([callback]) -> Promise**
- **nextEvents([callback]) -> Promise**

## Tests

To run the test suite, first install the dependencies, then run `npm test`:

```bash
$ npm install
$ npm test
```

## License
[MIT](https://github.com/efernandesng/placard-api/blob/master/LICENSE.md)
