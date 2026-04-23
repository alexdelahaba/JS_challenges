```js
function filterArray(arr){
    let filteredArray = arr.filter(item => typeof item === "number");
    return filteredArray
};



function filterArray(arr) {
    let filteredArr = [];
    for (let i = 0; i < arr.length; i++) {
      if ( typeof arr[i] !== "string") {
        filteredArr.push(arr[i])
      }
    } return filteredArr
};
```

Solution for problem 23.