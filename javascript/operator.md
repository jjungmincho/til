# Operator

## Numeric Operators

```jsx
console.log(1 + 1); // add
console.log(1 - 1); // substract
console.log(1 / 1); // divide
console.log(1 * 1); // multiply
console.log(1 % 1); // remainder
console.log(1 ** 1); // exponentiation
```

## Increment and decrement operators

### 1. Pre-increment

```jsx
let counter = 2;
const preIncrement = ++counter;
//counter = counter + 1;
//preIncrement = counter;
console.log(`preIncrement: ${preIncrement}, counter: ${counter}`); 
//preIncrement: 3, counter: 3
```

### 2. Post-increment

```jsx
const postIncrement = counter++;
//postIncrement = counter;
//counter = counter + 1;
console.log(`postIncrement: ${postIncrement}, counter: ${counter}`); 
//postIncrement: 3, counter: 4
```

### 3. Pre-decrement

```jsx
const preDecrement = --counter;
console.log(`preDecrement: ${preDecrement}, counter: ${counter}`); 
//preDecrement: 3, counter: 3
```

### 4. Post-decrement

```jsx
const postDecrement = counter--;
console.log(`postDecrement: ${postDecrement}, counter: ${counter}`); 
//postDecrement: 3, counter: 2
```

## Assignment operators

```jsx
let x = 3;
let y = 6;
x += y; // x = x + y;
x -= y; // x = x - y;
x *= y; // x = x * y;
x /= y; // x = x / y;
```

## Comparison operators

```jsx
console.log(10 < 6); //less than
console.log(10 <= 6); //less than or equal
console.log(10 > 6); //greater than
console.log(10 >= 6); //greater than or equal
```

```jsx
if (nullableObject != null) {
		nullableObject.something;
}

// if nullableObject is not null, do nullObject.something
```

## 3. ! (not)

```jsx
console.log(!value1); //true
```

## Reference
[DreamCoding](https://www.youtube.com/watch?v=YBjufjBaxHo&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2&index=4&ab_channel=%EB%93%9C%EB%A6%BC%EC%BD%94%EB%94%A9by%EC%97%98%EB%A6%AC)