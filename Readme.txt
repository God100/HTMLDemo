Git is a distributed version control system.
Git is free software.
Git has a mutable index called stage.
Git tracks changes of files.

$ git config --global user.name "Your Name"
$ git config --global user.email "email@example.com"

git init
git add <file>
git commit -m <message>

$ git log
$ git log --pretty=oneline
$ git reset --hard HEAD^    HEAD^^    HEAD~100
$ git reflog

$ git status

$ git reset HEAD <file>
$ git checkout -- file

$ git rm <file>