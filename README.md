# is-is-useless
a helpful way to check if a function is `is-useless`

some functions are `is-useless`, and some are not. this package provides a helpful way to distinguish the two categories of functions in a robust, modular way that will work with a variety of frameworks.

installation: `npm i is-is-useless`

usage: 
```js
const isUseless = require("is-useless");
const isIsUseless = require("is-is-useless");

isIsUseless(isUseless); // true
isIsUseless(() => {console.log("hello")}); // false
isIsUseless(null); // false

var ref = isUseless
isIsUseless(ref); // true
```

for help, contact ZestyLemonade#1012. i will not respond but you can get your anger of it not working out  by ranting

---

Changelog:

- v1.0.0: implements is-is-useless;
