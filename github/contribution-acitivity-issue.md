# How to solve contribution activity issue?

### Problem:
Github commits aren't recorded in "Your Contribution Calendar" 

### Reason:
Committing from my work computer where I was using a different email in my gitconfig

### Solution:
1. Open 'Git Bash'
2. Change directory to Github. Enter `cd documents/github` 
3. Check your current user email. Enter `git config user.email`
4. Then it will show an old email that you first registered with Github. 
5. Change the old user email. Enter `git config user.email "your email address used on your git repo"`
    - *Make sure to add the real email you are using for your git repo. Not just copy and paste "your email address used on your git repo."*

## Source
[Stackoverflow: GitHub commits aren't recorded in the 'Your Contributions` calendar](https://stackoverflow.com/questions/15289768/github-commits-arent-recorded-in-the-your-contributions-calendar)