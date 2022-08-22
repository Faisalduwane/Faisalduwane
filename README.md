#-*-coding:utf8;-*-
#qpy:console

print "This is console module"
$ sudo dnf install git-all 
$ sudo apt install git-all 
$ git --version 
$ sudo dnf install dh-autoreconf curl-devel expat-devel gettext-devel \
  openssl-devel perl-devel zlib-devel
$ sudo apt-get install dh-autoreconf libcurl4-gnutls-dev libexpat1-dev \
  gettext libz-dev libssl-dev
 
$ 
$ make configure
$ ./configure --prefix=/usr
$ make all doc info
$ sudo make install install-doc install-html install-info 
$ git clone git://git.kernel.org/pub/scm/git/git.git
 
$ git config --list --show-origin 
$ git config --global user.name "faisalduwane"
$ git config --global user.email faysalduwane410@gmail.com
$ git config --global core.editor emacs 
$ git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe'
-multiInst -notabbar -nosession -noPlugin"
 
$ git config --global init.defaultBranch main 
$ git config --list
user.name=faisalduwane 
user.email=faysalduwane410@gmail.com 
color.status=auto
color.branch=auto
color.interactive=auto
color.diff=auto
... 
$ git config user.name
faisalduwane 
$ git config --show-origin rerere.autoUpdate
file:/home/faisalduwane/.gitconfig false
 
$ git help <verb>
$ git <verb> --help
$ man git-<verb>
 
$ git help config 
$ git add -h
usage: git add [<options>] [--] <pathspec>...
  -n, --dry-run dry run
  -v, --verbose be verbose
  -i, --interactive interactive picking
  -p, --patch select hunks interactively
  -e, --edit edit current diff and apply
  -f, --force allow adding otherwise ignored files
  -u, --update update tracked files
  --renormalize renormalize EOL of tracked files (implies -u)
  -N, --intent-to-add record only the fact that the path will be added later
  -A, --all add changes from all tracked and untracked files
  --ignore-removal ignore paths removed in the working tree (same as --no
-all)
  --refresh don't add, only refresh the index
  --ignore-errors just skip files which cannot be added because of
errors
  --ignore-missing check if - even missing - files are ignored in dry run
  --chmod (+|-)x override the executable bit of the listed files
  --pathspec-from-file <file> read pathspec from file
  --pathspec-file-nul with --pathspec-from-file, pathspec elements are
separated with NUL character
 
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
nothing added to commit but untracked files present (use "git add" to track) 
$ git add README
 
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
  new file: README 
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  new file: README
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)
  modified: CONTRIBUTING.md 

$ git add CONTRIBUTING.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  new file: README
  modified: CONTRIBUTING.md 
$ git add CONTRIBUTING.md
$ git status
On branch master
Your branch is up-to-date with 'origin/master'.
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)
  new file: README
  modified: CONTRIBUTING.md 
$ git status -s
 M README
MM Rakefile
A lib/git.rb
M lib/simplegit.rb
?? LICENSE.txt
 
$ cat .gitignore
*.[oa]
*~ 




