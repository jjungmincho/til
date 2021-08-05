# How to undo my last push to Git using Git Bash?

```
git reset --hard HEAD@{1} //remove the last commit in your editors and git history in Git Bash 
git push -f //remove the last commit in your git repo 
```
**NOTE** This will not save your last commit in your editors. Do only when you save the last commit ahead. 

## Reference
[Is there a way to rollback my last push to Git?](https://stackoverflow.com/questions/6655052/is-there-a-way-to-rollback-my-last-push-to-git)