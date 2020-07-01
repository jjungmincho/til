# Promise

- A JavaScript object for asynchronous operations
- State: pending -> fulfilled or rejected
- Producer vs Consumer

1. Producer

- When new Promise is created, the executor runs automatically
- Doing some heavy work (network, read files)

```jsx
const promise = new Promise(((resolve, reject) => {
 console.log('doing something...);
 setTimeout() => {
     resolve('jess');
 }, 2000);
}))
```

2. Consumers: then, catch, fainally

```jsx
promise.then((value) => {
  console.log(value);
});
```

## Reference

[Dream Coding](https://www.youtube.com/watch?v=JB_yU6Oe2eE&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2&index=14)
