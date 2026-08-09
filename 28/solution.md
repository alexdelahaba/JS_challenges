```js

function factorial(num) {
    let fact = 1;
    for (let i = 0; i<num ; i++){
        fact *= (num-i);
    }
    return fact
};

function factorial(num){
    if (num < 0)
        return -1;
    else if (num == 0)
        return 1;
    else {
        return (num * factorial(num - 1));
    }
};

function factorial(num){
  let result = num;
  if (num === 0 || num === 1) return 1;
  while (num > 1) {
    num--;
    result *= num;
  }
  return result;
};

function factorial(num){
    let fact = num;
    if (num === 0 || num === 1) return 1;
    for (let i = num - 1; i >= 1; i--) {
      fact *= i;
    }
    return fact;
};

```

Solution for problem 28.