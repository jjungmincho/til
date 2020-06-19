# string

```jsx
1 const char = 'c';
2 const brendan = 'brendan';
3 const greeting = 'hello ' + brendan;
4 console.log(`value: ${greeting}, type: ${typeof greeting}`);
5 const helloBob = `hi ${brendan}!`; //template literals (string)
6 console.log(`value: ${helloBob}, type: ${typeof helloBob}`);
```

1, 2: Either one word or many words, they can all identified as string.

3: You can add a variable after a string by using `+`. The type will be still identified as string.

4, 5: Use template literals (string) ``. This is easier and faster than using ' ' or " ".
