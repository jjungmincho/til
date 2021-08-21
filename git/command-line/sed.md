# sed 

- stand for "stream editor"
- find and replace 

```
sed 's/snow/rain/' abc.txt
sed 's/snow/rain/g' abc.txt
```

- `s`: substitution ** always used when using `sed` for substitution
- `snow`: the search string or the text to find
- `rain`: the replacement string or the text to ad in place
- `g`: the search global throughout the file 

## Reference
[codecademy](https://www.codecademy.com/courses/learn-the-command-line)