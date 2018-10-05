# Hello Git!

Welcome to NOW's practice git repository where you can make as many mistakes as you'd like and learn git while doing it.
Feel free to make and send us pull requests about anything and discover how git and github work.

## Useful Links

+ Git Cheat Sheet (A list of cool features of Git and GitHub): https://github.com/tiimgreen/github-cheat-sheet
+ Pro Git Book: https://git-scm.com/book
+ GitHub Hello World Guide: https://guides.github.com/activities/hello-world/
+ More resources: https://try.github.io/

## Instructions

It's as easy as 5 steps.

+ Fork this repository
+ Make a new branch in your fork
+ Add stuff to your branch
+ Commit your changes
+ Send us a pull request!

You can use the Git CLI or the GitHub interface to complete these tasks.

+ Download the Git CLI from here: [https://git-scm.com/downloads]
+ Make an account on GitHub here: [https://github.com/join]

## Common Git commands

+ ### Clone a Git repository
```sh
git clone https://github.com/username/repository
```
Replace _username_ and _repository_ with the details of the repository you want to clone.


+ ### Add files
To add a single file with name _filename_
```sh
git add <filename>
```
To add a list of files
```sh
git add <list of files>
```
Example:  `git add file1.txt file2.txt file3.txt`

To add all files that have changed. `git add --all` can also be used.
```sh
git add .
```


+ ### Remove files
```sh
git rm <filename>
```
`rm` command can be used like the `add` command to remove multiple files at once by providing a list of files to be removed.


+ ### Get status of the files that have been modified and staged
```sh
git status -s
```
(M) - Modified, (A) - Added, (AM) - File hasn't been altered since it was last added


+ ### Commit all files that have been staged
```sh
git commit -m "your commit message here"
```


+ ### View commit history
```sh
git log
```
To get all changes that have been committed so far, in the order that they have been committed in do `git log --summary`


+ ### Get staged differences and displays what has changed since our last commit
```sh
git diff --staged
```


+ ### Pull changes from remote repository and sync your local repository
```sh
git pull
```


+ ### Pulls changes from origin repository but doesn't merge them
```sh
git fetch
```


+ ### Make a new branch
```sh
git branch <branchname>
```


+ ### Merge branches into master
```sh
git merge <branchname>
```


+ ### Delete a branch
```sh
git branch -d <branchname>
```


+ ### List all remote branches
```sh
git branch -r
```


+ ### Help
```sh
git help
```
