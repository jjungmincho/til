# Callback function

A callback function is a function passed into another function as an argument, which is then invoked inside the outer function to complete some kind of routine or action.

- Synchronous callback

```jsx
function printImediately(print) {
    print();
}
print Immediately(() => console.log('hello'));
```

- Asynchronous callback

```jsx
function printWithDelay(print, timeout) {
  setTimeout(print, timeout);
}
printWithDelay(() => console.log("async callback"), 2000);
```

## Reference

[MDN web docs](https://developer.mozilla.org/en-US/docs/Glossary/Callback_function)
[DreamCoding](https://www.youtube.com/watch?v=s1vpVCrT8f4&list=PLv2d7VI9OotTVOL4QmPfvJWPJvkmv6h-2&index=13)
