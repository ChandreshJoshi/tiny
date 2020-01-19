# tiny
Ref:  https://www.freecodecamp.org/news/how-to-make-a-beautiful-tiny-npm-package-and-publish-it-2881d4307f78/

      https://shields.io/
      
      https://docs.npmjs.com/creating-node-js-modules
      
      https://www.npmjs.com/package/@cjoshi/tiny


npm (scoped)npm bundle size (minified)

Removes all spaces from a string.

Install:
$ npm install @cjoshi/tiny


--------------------------------
# @cjoshi/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@cjoshi/tiny.svg)](https://www.npmjs.com/package/@cjoshi/tiny)
[![npm bundle size (minified)](https://img.shields.io/cjoshi/min/@cjoshi/tiny.svg)](https://www.npmjs.com/package/@cjoshi/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @cjoshi/tiny
```

## Usage

```js
const tiny = require("@cjoshi/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```
