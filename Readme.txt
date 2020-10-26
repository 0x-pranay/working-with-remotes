What is the best workflow ?

-------------------------------
Git Basic
-----------------------------



1. Install
sudo apt install git-all

2. Configure

    git config --global user.name pranay

    git config --global user.email pranay@soal.io



3. Initialize Git
   git init



How to commit?
  1. Make some change ie. adding a new file or modify existing one
     $ touch newFile.txt
  2. Bring those whose which you want to add ina  commit to staging/index
     $ git add newFile.txt
  3. git commit
         opens a edit to write the commit message



How to view the commits /logs

 $ git log
 $ git log --oneline

To See the difference between my file in working directory  to file in the staging area
 git diff  <fileName>

To see the change between my file in staging area and the same file in local repository
git diff --staged



