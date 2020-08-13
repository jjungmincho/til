# `eval(string)`

**Warning**: Executing JavaScript from a string is an enormous security risk. It is far too easy for a bad actor to run arbitrary code when you use eval(). See Never use eval()!, below.

Use functions instead of evaluating snippets of code.
JavaScript has first-class functions, which means you can pass functions as arguments to other APIs, store them in variables and objects' properties, and so on. Many DOM APIs are designed with this in mind, so you can (and should) write:

```
// instead of setTimeout(" ... ", 1000) use:
setTimeout(function() { ... }, 1000);

// instead of elt.setAttribute("onclick", "...") use:
elt.addEventListener('click', function() { ... } , false);
```

Closures are also helpful as a way to create parameterized functions without concatenating strings.

## Reference

[Mdn](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/eval)
