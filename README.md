# @diotoborg/necessitatibus-nam-tempora <sup>[![Version Badge][npm-version-svg]][package-url]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][npm-badge-png]][package-url]

Give a regex, get a robust predicate function that tests it against a string. This will work even if `RegExp.prototype` is altered later.

## Getting started

```sh
npm install --save @diotoborg/necessitatibus-nam-tempora
```

## Usage/Examples

```js
var regexTester = require('@diotoborg/necessitatibus-nam-tempora');
var assert = require('assert');

var tester = regexTester('a');
assert.ok(tester('a'));
assert.notOk(tester('b'));
```

## Tests
Simply clone the repo, `npm install`, and run `npm test`

[package-url]: https://npmjs.org/package/@diotoborg/necessitatibus-nam-tempora
[npm-version-svg]: https://versionbadg.es/ljharb/@diotoborg/necessitatibus-nam-tempora.svg
[deps-svg]: https://david-dm.org/ljharb/@diotoborg/necessitatibus-nam-tempora.svg
[deps-url]: https://david-dm.org/ljharb/@diotoborg/necessitatibus-nam-tempora
[dev-deps-svg]: https://david-dm.org/ljharb/@diotoborg/necessitatibus-nam-tempora/dev-status.svg
[dev-deps-url]: https://david-dm.org/ljharb/@diotoborg/necessitatibus-nam-tempora#info=devDependencies
[npm-badge-png]: https://nodei.co/npm/@diotoborg/necessitatibus-nam-tempora.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@diotoborg/necessitatibus-nam-tempora.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@diotoborg/necessitatibus-nam-tempora.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@diotoborg/necessitatibus-nam-tempora
[codecov-image]: https://codecov.io/gh/ljharb/@diotoborg/necessitatibus-nam-tempora/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/ljharb/@diotoborg/necessitatibus-nam-tempora/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/ljharb/@diotoborg/necessitatibus-nam-tempora
[actions-url]: https://github.com/diotoborg/necessitatibus-nam-tempora/actions
