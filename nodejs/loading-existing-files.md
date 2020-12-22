# Loading Existing Files
Node REPL can also load existing JS files. If we had the following code saved into script.js:

```bash
var a = 'Node REPL is fun!';
```

We can use `.load` to load it into the REPL. `.load` takes a path argument, so to load script.js we would use `.load ./script.js`.

```bash
$ node
> .load ./script.js
var a = 'Node REPL is fun!';
 
> a
'Node REPL is fun!'
```

After the script file is loaded, the variables are accessible in the REPL, so when we evaluate the `a` variable, it’s value has been set by loading `script.js`, and ‘Node REPL is fun!’ prints to the console.

## Reference
[REPL Doc](https://nodejs.org/api/repl.html)

[Codecademy](https://www.codecademy.com/paths/full-stack-engineer-career-path/tracks/fscp-javascript-syntax-part-i/modules/fscp-running-javascript/articles/what-is-node)

