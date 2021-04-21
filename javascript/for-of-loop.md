# for...of loop

- the `for...of` loop has a simpler syntax which can be beneficial for code readability, especially in larger and more complex applications
- to reclaim some control of how iteration is managed:
    - using JavaScript’s break and continue statements

```js
const pokemonList = ['Pikachu', 'Charizard', 'Squirtle', 'Yoshi', 'Snorlax'];

// Write your code below
for( const pokemon of pokemonList){
  if ( pokemon === 'Yoshi'){
    continue;
  }
  console.log(`You caught a ${pokemon}!`);
}

/* 
//OUTPUT: 
You caught a Pikachu!
You caught a Charizard!
You caught a Squirtle!
You caught a Snorlax!
*/
```

## Reference
[The for...of Loop | Codecademy](https://www.codecademy.com/paths/front-end-engineer-career-path)