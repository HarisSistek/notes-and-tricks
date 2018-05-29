
# ECMAScript 2016+

Keep track of new Javascript and useful code examples. 

[1] Examples taken from: https://medium.freecodecamp.org/here-are-examples-of-everything-new-in-ecmascript-2016-2017-and-2018-d52fa3b5a70e

## Array.prototype.includes

includes is a simple instance method on the Array and helps to easily find if an item is in the Array (including NaN unlike indexOf).

```javascript
const arr = [1, 2, 3, 4,NaN];

// instead of 
if (arr.indexOf(3) >= 0) {
  console.log(true);
}

// use
if (arr.includes(3)) {
  console.log(true);
}

// indexOf doesn't work for NaN
arr.includes(NaN); // true
arr.indexOf(NaN);  // -1 (doesn't work)


```
