```js
function findLargestNums(arr){
    let newArr = []
    for (let i = 0; i < arr.length; i++) {
        newArr.push(Math.max(...arr[i]));
    }
    return newArr
};
```

Solution for problem 35.