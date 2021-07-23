# mkdir
- Stands for “make directory”
- Takes in a directory name as an argument and then creates a new directory in the current working **directory**
- What if we wanted to create another directory inside that one? We could `cd` into **media** and then use `mkdir`, or we could make the new directory from our current position by using a `/` to combine arguments.

```
$ mkdir media/tv
$ pwd
/home/ccuser/workspace/blog/2014/dec
$ ls
media monitor.txt mouse.txt
```

## Reference
[Codecademy: Command Line for Building Websites](https://www.codecademy.com/learn/paths/full-stack-engineer-career-path/tracks/fscp-setting-up-your-dev-environment/modules/fecp-command-line-for-building-websites/cheatsheet)