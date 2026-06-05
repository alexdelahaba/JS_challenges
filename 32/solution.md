```js
function isOrthogonal(arr1, arr2){
    let ortho = 0;
    for (i = 0; i < arr1.length; i++){
        ortho += arr1[i]*arr2[i]
    }
    if (ortho === 0) {
        return true
    }
    return false
};
```

Solution for problem 32.