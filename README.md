# @hugorbs/tiny

![npm](https://img.shields.io/npm/v/@hugorbs/tiny.svg)
![npm bundle size](https://img.shields.io/bundlephobia/min/@hugorbs/tiny.svg)

Removes all spaces from a string.

## Install

```
$ npm install @bamblehorse/tiny
```

## Usage

```js
const tiny = require("@bamblehorse/tiny");

tiny("So much space!");
//=> "Somuchspace!"

tiny(1337);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
```