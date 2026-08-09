```js
function countVowels(str){
    let count = 0;
    let vowlStr = str.toLowerCase().match(/(a|e|i|o|u)/g);
    for (let i = 0; i < vowlStr.length; i++) {
        count += 1;
    }
    return count;
};
```

Solution for problem 31.