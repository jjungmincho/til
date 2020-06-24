# Getter and Setter

```jsx
class User {
  constructor(firstName, lastName, age) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.age = age;
  }

  get age() {
    return this._age;
  }

  set age(value) {
    this._age = value < 0 ? 0 : value; // 0
  }
}

const user1 = new User("Steve", "Jobs", -1);
console.log(user1.age);
```

When you find a clear mistake, you can correct it by using 'getter and setter'

In this example, people cannot have a negative age. So set `get` first to return `this.age` and add `_` to avoid "class.js:33 Uncaught RangeError: Maximum call stack size exceeded."

In `set`, you can either give a direct error message like:

```
if (value < 0) {throw Error("age can not be negative");}
```

or
give a new value in age as if the value is less than 0, set the age to 0 or the value.

## Reference:

[Dream Coding](https://youtu.be/_DLhUBWsRtw)
