# 30. Use a regular expression to match characters that are not letters, digits, or spaces.

```js
function matchAny(str){
      //Write Your solution Here
};


console.log(matchAny('Csxdzontains_underscore ')); //[ '_' ]
console.log(matchAny('Csxdzontains_underscore $ * P')); //[ '_', '$', '*' ]
```

> Implement matchAny with a regex matching non-alphanumeric non-space characters.