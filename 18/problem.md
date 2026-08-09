# 18. Receive two zero-argument functions `f` and `g`; call both and return which one produced the larger result as a string.

```js
function whichIsLarger(f, g){
      //Write Your solution Here
};

console.log(whichIsLarger(() => 25, () => 15)); // f
console.log(whichIsLarger(() => 25, () => 25)); // neither
console.log(whichIsLarger(() => 25,  () => 50)); // g
```

> Implement whichIsLarger to call both functions and compare results.