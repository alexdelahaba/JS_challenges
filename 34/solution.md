```js
function removeVowels(str){
    let newArr = str.match(/[^aeiouAEIOU]/g);
    let newString = newArr.join('');
    return newString
};
```

Solution for problem 34.