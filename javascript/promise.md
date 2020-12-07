# Promise

- The **Promise** object represents the eventual completion (or failure) of an asynchronous operation and its resulting value instead of using callback function.
- A **Promise** is in one of these states: pending → fulfilled or rejected
    - ***pending***: initial state, neither fulfilled nor rejected.
    - ***fulfilled***: meaning that the operation was completed successfully.
    - ***rejected***: meaning that the operation failed.
- **Producer** vs **Consumer**
    - producer: 정보를 제공하는 자
    - consumer: 정보를 소비하는 자

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
### then

> The `then()` method returns a Promise. It takes up to two arguments: callback functions for the success and failure cases of the Promise.

### catch

> The `catch()` method returns a Promise and deals with rejected cases only.

### finally

> The `finally()` method returns a Promise. When the promise is settled, i.e either fulfilled or rejected, the specified callback function is executed. This provides a way for code to be run whether the promise was fulfilled successfully or rejected once the Promise has been dealt with.


```jsx
promise.then((value) => {
  console.log(value);
});
```

## Reference

[Dream Coding](https://www.youtube.com/watch?v=JB_yU6Oe2eE&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2&index=14)
