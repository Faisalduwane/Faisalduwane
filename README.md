$ cd /home/user/my_project 
$ git init
 
$ git add *.c
$ git add LICENSE
$ git commit -m 'Initial project version'
 
$ git clone https://github.com/libgit2/libgit2
 
$ git clone https://github.com/libgit2/libgit2 mylibgit
 
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
nothing to commit, working tree clean
 
$ echo 'My Project' > README
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)
  README
