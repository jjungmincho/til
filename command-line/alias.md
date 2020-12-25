# alias 

 If you don’t want to type the entire text of each of the Git commands, you can easily set up an alias for each command using git config.

 ```bash
 $ git config --global alias.st status
 $ git st
 On branch master
 No commits yet
 nothing to commit (create/copy files and use "git add" to track)
 ```

**Note: this `git st` operation must be run in a work tree**
``` 
Jessica@DESKTOP-6MOIREO MINGW64 ~/documents/git/.git (GIT_DIR!)
$ git st
fatal: this operation must be run in a work tree
```

## Reference
[git documentation](https://git-scm.com/book/en/v2/Git-Basics-Git-Aliases)