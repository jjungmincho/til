# add

## add * (asterisk) vs add . (period)
`add *` means add all files in the current directory, except for files whose name begin with a dot. This is your shell functionality and Git only ever receives a list of files.

`add .` has no special meaning in your shell, and thus Git adds the entire directory recursively, which is almost the same, but including files whose names begin with a dot.

## Reference
[Stackoverflow: git add * (asterisk) vs git add . (period)
](https://stackoverflow.com/questions/26042390/git-add-asterisk-vs-git-add-period)