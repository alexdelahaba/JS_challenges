```js
function maximumScore(tileHand){
  let score = 0;
  for ( let i = 0; i < tileHand.length; i++) {
    score += tileHand[i].score;
  }
  return score;
};
```

Solution for problem 36.