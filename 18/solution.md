```js
function whichIsLarger(f, g){
    if (f() > g()) {
        return ('f')
    }
    else if (g() > f()) {
        return ('g')
    }
    else if (f() === g()) {
        return ('neither')
    }
};
```

Solution for problem 18.