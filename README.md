mess
====

Missing shuffle function for arrays in javascript.
This is [Fisher–Yates shuffle](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle), and it's very fast.

## Installation

```
npm install mess
```

## Usage

```javascript
var mess = require("mess");

console.log(mess([1,2,3,4,5,6,7,8,9,0]));
// output will be something like:
// [ 7, 9, 2, 0, 6, 8, 5, 3, 1, 4 ]
```

## Why mess

Because naming modules is hard and shuffle is already taken.

## Authors

* [Ronald Fisher and Frank Yates](https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle)
* [People on internet](http://stackoverflow.com/questions/6274339/how-can-i-shuffle-an-array-in-javascript#6274398)
