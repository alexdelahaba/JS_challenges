```js

function doubleChar(str) {
    let doubleString = '';
    for(let i=0; i<str.length; i++){
        doubleString += str[i] + str[i]
    }
    return doubleString
};

function doubleChar(str){
    let array = str.split("");
    let array2 = array.map( x => x.repeat(2));
    let doubleString = array2.join("");
    return doubleString
};

```

Solution for problem 27.