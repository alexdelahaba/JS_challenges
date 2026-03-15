```js
function minMax(arr){
    arr.sort(function(a, b){return(a - b)})
    return [arr[0], arr[arr.length - 1]]
};
```

Solution for problem 15.