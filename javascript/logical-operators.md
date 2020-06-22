# Logical operators: || (or), && (and), ! (not)

```
const value1 = false;
const value2 = 4 < 2;
```

## 6-1. || (or)

```jsx
console.log(`or: ${value1 || value2 || check()}`);

function check() {
  for (let i = 0; i < 10; i++) {
    //wasting time
    console.log("omg");
  }
  return true;
}
```

**Note!! If** `value1 = true;`

```jsx
const value1 = true;
const value2 = 4 < 2;

console.log(`or: ${value1 || value2 || check()}`);

function check() {
  for (let i = 0; i < 10; i++) {
    //wasting time
    console.log("omg");
  }
  return true;
}
```

Do not recommend to use 'heavy operator' at the first value because it will slow down the process.

## 6-2. && (and)

```jsx
console.log(`or: ${value1 && value2 && check()}`);

function check() {
  for (let i = 0; i < 10; i++) {
    //wasting time
    console.log("omg emoji");
  }
  return true;
}
```

Because `value1` is already false, it is not going to waste time of checking `value2` and `check()` values. Therefore, it will result 'false'.

## 6-3. ! (not)

```jsx
console.log(!value1);
```

`!` changes the value of the operator.

For example, `value1` was true before. Now it became false.
