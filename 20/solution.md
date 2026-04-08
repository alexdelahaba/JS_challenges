```js
function largestSwap(num){
    let num1 = num + "";
    let num2 = num1.split("").reverse().join("");
    if (num1 >= num2) {
        return true;
    }
    if (num1 < num2) {
        return false;
    }
};
```

Solution for problem 20.