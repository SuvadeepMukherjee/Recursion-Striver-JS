# Re-1

Recursion with base case

```js
let cnt = 0;

function f() {

  if (cnt == 4) return;

  console.log(cnt);

  cnt++;

  f();

}

f();
```

