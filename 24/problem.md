# 24. Using a regular expression, extract all occurrences of "red flag" and "blue flag" from a given string.

```js
function matchFlag(str){
      //Write Your solution Here
};

console.log(matchFlag("yellow flag red flag blue flag green flag")); //[ 'red flag', 'blue flag' ]
console.log(matchFlag("yellow flag green flag orange flag white flag")); //null
console.log(matchFlag("yellow flag blue flag green flag")); //[ 'blue flag' ]
```

> Implement matchFlag using a regex.