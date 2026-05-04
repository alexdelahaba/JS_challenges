# 25. Use a RegExp to find sequences of three or more consecutive dots (ellipses) inside a string.

```js
function matchEllipsis(str){
      //Write Your solution Here
};

console.log(matchEllipsis("Hello!... How goes?.....")); //[ '...', '.....' ]
console.log(matchEllipsis("good morning!..... How goes?.")); // [ '.....' ]
console.log(matchEllipsis("good night!.......... How goes?...")); // [ '..........', '...' ]
```

> Implement matchEllipsis with a regex.