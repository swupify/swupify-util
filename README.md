## Swupify Util
# A NPM Util Package


- # Generate Numeric ID
```js
const swupify = require('swupify-util');
const length = 5; // Length of the Numeric ID
console.log(swupify.generateNumericID(length)); // 48956 | random numeric ID
```


- # Generate ID (URL Friendly + Non URL Friendly)
```js
const swupify = require('swupify-util');
const length = 5; // Length of the ID
const url_friendly = true;
console.log(swupify.generateID(length, url_friendly)); // gsp_5 | random URL friendly ID
// OR
const url_friendly = false;
console.log(swupify.generateID(length, url_friendly)); // ye#5_ | random Non URL friendly ID
```


- # Pick a random item from an Array
```js
const swupify = require('swupify-util');
const array = ['foo', 'bar'];
console.log(swupify.randomize(array)); // 'bar' | random item from the "array"
```
