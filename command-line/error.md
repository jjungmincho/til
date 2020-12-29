# Git Error List

## Git error - Fatal: Not a git repository

This error means you attempted to run a Git command, but weren’t inside a Git repository. Make sure you’ve:

- Navigated to the right directory. Check with `ls`.
- **Initialized your repository with `git init` or by cloning an existing repo.**

## Reference
[datree.io](https://www.datree.io/resources/git-error-fatal-not-a-git-repository)

---

## fatal: This operation must be run in a work tree
 You are probably inside the `.git` subfolder, move up one folder to your project root. OR you are not even to any folders. Make sure to navigate to the right directory. 

 My problem:
 ```
 $ git difftool
fatal: difftool requires worktree or --no-index
```

Reason:
```
$ pwd
/c/Users/Jessica
```

Solution:
```
$ cd documents/git
```
```
$ git difftool

Viewing (1/1): 'a.txt'
Launch 'vscode' [Y/n]? Y
```

## Reference
[stackoverflow](https://stackoverflow.com/questions/1456923/why-am-i-getting-the-message-fatal-this-operation-must-be-run-in-a-work-tree)