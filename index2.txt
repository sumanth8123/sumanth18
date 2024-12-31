mkdir 3VC20CS065
ls
cd 3VC20CS065
Git init
Git config-list
git config –global user.name “lingarajpower”
git config – global user.email “ lingarajpower@gmail.com”
Git clone https://github.com/lingarajpower/3VC15CS065.git
cd 3VC15CS065
git status
echo "hello git and git Hub" >> lab1.txt
git add lab1.txt
git status
Git commit –m “first msg”
Git push origin main
vi one.c
git add one.c
Git commit –m “create one.c”
git add two.c
git commit -m "create two.c"
git log
git status
$ git branch b1
git branch b2
git branch
Git checkout b1
Git status
$ echo " in branch b1 hello world " >> lab3.c
$ echo " in branch b1 branching world " >> lab4.c
git add lab3.c
git add lab4.c
git commit -m " lab3 for b1"
git checkout b2
git branch
echo " in branch b2 hello world" >> lab5.c
echo " in branch b2 branching world" >> lab6.c
git add lab5.c
git add lab6.c
git commit -m " lab5 and lab 6 in branch b2"
git checkout master
git diff main..b1
git merge b1
git branch –merged
git branch -d b1
git branch -d b2
$ git status
git merge b2
git branch –-merged
git branch -d b2
vi index.txt
git add .
$ git commit -m "create indes file"
$ git branch feature
$ git checkout feature
vi feature.txt
git add.
$ git commit -m "work in progress"
$ vi index.txt
$ git status
git checkout main
git stash
Git status
git stash list
git checkout main
git checkout feature
git stash pop
$ git stash list
$ git add .
git commit -m "create indes file changed in feature"
