```js
function isJS(path){
    let extension = path.match( /[^.]+$/g)[0]
    if(extension === 'js' || extension==='jsx'){
        return true;
    }
    return false;
};
```

Solution for problem 37.