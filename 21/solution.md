```js
function charCount(myChar, str){
    let a = 0;
    for (let i = 0; i < str.length; i++) {
      if (myChar.toLowerCase() === str.toLowerCase()[i]) {
        a += 1;
      }
    }
    return a
};
```

Solution for problem 21.