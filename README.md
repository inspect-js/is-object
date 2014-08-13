# is-object

[![build status][1]][2] [![dependency status][3]][4] [![dev dependency status][9]][10]

[![browser support][5]][6]

Checks whether a value is an object

Because `typeof null` is a troll.

## Example

```js
var isObject = require("is-object")

console.log(isObject(null)) // false
console.log(isObject(require("util"))) // true
```

## Installation

`npm install is-object`

## Contributors

 - [Raynos][7]
 - [Jordan Harband][8]

## MIT Licensed

  [1]: https://secure.travis-ci.org/ljharb/is-object.svg
  [2]: http://travis-ci.org/ljharb/is-object
  [3]: http://david-dm.org/ljharb/is-object/status.svg
  [4]: http://david-dm.org/ljharb/is-object
  [5]: http://ci.testling.com/ljharb/is-object.svg
  [6]: http://ci.testling.com/ljharb/is-object
  [7]: https://github.com/Raynos
  [8]: https://github.com/ljharb
  [9]: https://david-dm.org/ljharb/is-object/dev-status.svg
  [10]: https://david-dm.org/ljharb/is-object#info=devDependencies
