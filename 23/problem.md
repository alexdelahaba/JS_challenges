# 23. From a mixed array of numbers and strings, return a new array containing only the numeric entries.

```js
function filterArray(arr){
      //Write Your solution Here
};

console.log(filterArray([1, 'z', 4, 5, 'i', 9, 'm'])); //[ 1, 4, 5, 9 ]
console.log(filterArray([8, 'z', 1, '8', 'i', 9, 'm'])); //[ 8, 1, 9 ]
console.log(filterArray([7, '1', 'z', 0, 'i', 9, 'm'])); //[ 7, 0, 9 ]
```

> Implement filterArray to exclude strings.