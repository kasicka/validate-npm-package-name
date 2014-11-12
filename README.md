# valid-npm-package-name 

Is the given string an acceptable npm package name?

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install valid-npm-package-name --save
```

## Usage

```js
var valid = require("valid-npm-package-name")

// true
valid("some-package")
valid("example.com")
valid("CAPITAL-LETTERS")
valid("under_score")
valid("123numeric")
valid("crazy!")

// false
valid("")
valid(" leading-space")
valid("trailing-space ")
valid("s/l/a/s/h/e/s")

```

## Tests

```sh
npm install
npm test
```

## Dependencies

None

## Dev Dependencies

- [tap](https://github.com/isaacs/node-tap): A Test-Anything-Protocol library


## License

ISC

_Generated by [package-json-to-readme](https://github.com/zeke/package-json-to-readme)_