# JS30 - Day 7 - Array Cardio 22
## Array.prototype.find()
filter() but returns the first item that we are looking for and findIndex() gives it's index.

## Array.prototype.splice() without changing the originial array:
```js
Array.splice(index, 1);
// to =>
[
    ...Array.slice(0, index),
    ...Array.slice(index)
]
```