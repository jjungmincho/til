# How to create a new branch with git and manage branches

1. Before creating a new branch, pull the changes from upstream. Your master needs to be up to date:
```
$ git pull
```

2. Check all the branches created by using:
```
// local
$ git branch

// server 
$ git branch --all
```

3. Create the branch on your local machine:
```
$ git branch [name_of_your_new_branch]
```

4. Switch to your...:
```
// new branch
$ git switch [name_of_your_new_branch]

// master
$ git switch master
```

OR 

Create the branch on your local machine **and switch in this branch** :
```
$ git switch -C [name_of_your_new_branch]
```

## Reference
[Create a new branch with git and manage branches by Kunena](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)