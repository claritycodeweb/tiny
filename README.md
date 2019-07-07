# @claritycodeweb/tiny

[![npm (scoped)](https://img.shields.io/npm/v/@claritycodeweb/tiny.svg)](https://www.npmjs.com/package/@claritycodeweb/tiny)
[![npm bundle size (minified)](https://img.shields.io/bundlephobia/min/@claritycodeweb/tiny.svg)](https://www.npmjs.com/package/@claritycodeweb/tiny)

Removes all spaces from a string.

## Install

```
$ npm install @claritycodeweb/tiny
```

## Usage

```js
const tiny = require("@claritycodeweb/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```