# Nesting Selectors

- the process of placing selectors inside the scope of another selector

```sass
.parent {
  color: blue;
  .child {
    font-size: 12px;
  }
}

// this is same as...

.parent {
  color: blue;
}

.parent .child {
    font-size: 12px;
}
```

## Reference

[Codecademy](www.codecademy.com)
