# symbol

Symbol creates an unique identifier for objects

```jsx
const symbol1 = Symbol("id");
const symbol2 = Symbol("id");
console.log(symbol1 === symbol2); //false
```

Even if you write the same symbols, they are different.

If you want to make them true, include `.for` after `symbol`:

```jsx
const gSymbol1 = Symbol.for("id");
const gSymbol2 = Symbol.for("id");
console.log(gSymbol1 === gSymbol2); //true
```

Note there will be an error if you don't add `.description` !

```jsx
console.log('value: ${symbol1.description}, type: ${typeof symbol1}`);
```
