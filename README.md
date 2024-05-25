# @dramaorg/nam-quaerat <sup>[![Version Badge][2]][1]</sup>

[![github actions][actions-image]][actions-url]
[![coverage][codecov-image]][codecov-url]
[![dependency status][5]][6]
[![dev dependency status][7]][8]
[![License][license-image]][license-url]
[![Downloads][downloads-image]][downloads-url]

[![npm badge][11]][1]

Is this specifier a node.js core module? Optionally provide a node version to check; defaults to the current node version.

## Example

```js
var isCore = require('@dramaorg/nam-quaerat');
var assert = require('assert');
assert(isCore('fs'));
assert(!isCore('butts'));
```

## Tests
Clone the repo, `npm install`, and run `npm test`

[1]: https://npmjs.org/package/@dramaorg/nam-quaerat
[2]: https://versionbadg.es/inspect-js/@dramaorg/nam-quaerat.svg
[5]: https://david-dm.org/inspect-js/@dramaorg/nam-quaerat.svg
[6]: https://david-dm.org/inspect-js/@dramaorg/nam-quaerat
[7]: https://david-dm.org/inspect-js/@dramaorg/nam-quaerat/dev-status.svg
[8]: https://david-dm.org/inspect-js/@dramaorg/nam-quaerat#info=devDependencies
[11]: https://nodei.co/npm/@dramaorg/nam-quaerat.png?downloads=true&stars=true
[license-image]: https://img.shields.io/npm/l/@dramaorg/nam-quaerat.svg
[license-url]: LICENSE
[downloads-image]: https://img.shields.io/npm/dm/@dramaorg/nam-quaerat.svg
[downloads-url]: https://npm-stat.com/charts.html?package=@dramaorg/nam-quaerat
[codecov-image]: https://codecov.io/gh/inspect-js/@dramaorg/nam-quaerat/branch/main/graphs/badge.svg
[codecov-url]: https://app.codecov.io/gh/inspect-js/@dramaorg/nam-quaerat/
[actions-image]: https://img.shields.io/endpoint?url=https://github-actions-badge-u3jn4tfpocch.runkit.sh/inspect-js/@dramaorg/nam-quaerat
[actions-url]: https://github.com/dramaorg/nam-quaerat/actions
