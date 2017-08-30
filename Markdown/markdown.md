# Markdown assignment
# Git workflow


## What is Git
Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people. It is primarily used for source code management in software development, but it can be used to keep track of changes in any set of files. As a distributed revision control system it is aimed at speed,data integrity, and support for distributed, non-linear workflows.

## importance of good documentation
Good documentation is key to the success of any project. Making documentation accessible enables people to learn about a project; making it easy to update ensures that documentation stays relevan.

## common comands in git

* `git status`
show modified files in working directory, staged for your next commit
* `git add [file]`
add a file as it looks now to your next commit (stage)
* ```git reset [file]```
unstage a file while retaining the changes in working directory
* `git diff`
diff of what is changed but not staged
* ```git branch```
list your branches. a * will appear next to the currently active branch
* `git branch [branch-name]`
create a new branch at the current commit
* `git checkout`
switch to another branch and check it out into your working directory
* `git merge [branch]`
merge the specified branch’s history into the current one