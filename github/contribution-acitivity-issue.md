# How to solve contribution activity issue?

### Problem:
Github commits aren't recorded in "Your Contribution Calendar" 

### Reason:
Committing from my work computer where I was using a different email in my gitconfig

### Solution:
1. Open 'Git Bash'
2. Change directory to Github. Enter `$ cd documents/github` 
3. Check your current user email. Enter `$ git config user.email`
4. Then it will show an old email that you first registered with Github. 
5. Change the old user email. Enter `$ git config --global user.email "email@example.com"`

## Source
[Stackoverflow: GitHub commits aren't recorded in the 'Your Contributions` calendar](https://stackoverflow.com/questions/15289768/github-commits-arent-recorded-in-the-your-contributions-calendar)

[Github Docs: Setting your commit email address](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-user-account/managing-email-preferences/setting-your-commit-email-address#about-commit-email-addresses)