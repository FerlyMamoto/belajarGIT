# belajarGIT
Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT
$ git clone https://github.com/FerlyMamoto/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT
$ git init
Initialized empty Git repository in C:/GIT/.git/
Initialized empty Git repository in C:/GIT/.git/
bash: Initialized: command not found

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT (master)
$ cd belajarGIT

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-git

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 39e58ce] tugasgit
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating 3774a63..39e58ce
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 290 bytes | 290.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/FerlyMamoto/belajarGIT.git
   3774a63..39e58ce  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-html

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git commit -m "tugashtml"
[Tugas-html c3381f6] tugashtml
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git status
On branch Tugas-html
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-html
Updating 39e58ce..c3381f6
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 319 bytes | 106.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/FerlyMamoto/belajarGIT.git
   39e58ce..c3381f6  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-css

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git add Tugas-Css.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git commit -m "tugasCSS"
[Tugas-css 7368584] tugasCSS
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git status
On branch Tugas-css
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-css
Updating c3381f6..7368584
Fast-forward
 Tugas-Css.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-Css.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 340 bytes | 85.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/FerlyMamoto/belajarGIT.git
   c3381f6..7368584  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-js

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "TugasJS"
[Tugas-js 041a308] TugasJS
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating 7368584..041a308
Fast-forward
 Tugas-Js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Js.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 286 bytes | 143.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FerlyMamoto/belajarGIT.git
   7368584..041a308  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "TugasJS"
On branch Tugas-js
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git add Tugas-Js.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git commit -m "TugasJS"
[Tugas-js 889e6cb] TugasJS
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git status
On branch Tugas-js
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-js
Updating 041a308..889e6cb
Fast-forward
 Tugas-Js.txt | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 263 bytes | 131.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FerlyMamoto/belajarGIT.git
   041a308..889e6cb  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-midProject

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git add Tugas-MidProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git commit -m "tugasmidproject"
[Tugas-midProject c54f91d] tugasmidproject
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-MidProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git status
On branch Tugas-midProject
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 889e6cb..c54f91d
Fast-forward
 Tugas-MidProject.txt | 0
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-MidProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 277 bytes | 277.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FerlyMamoto/belajarGIT.git
   889e6cb..c54f91d  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-php

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasPHP"
[Tugas-php 1743388] tugasPHP
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git merge Tugas-php
Already up to date.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$  git merge Tugas-php
Updating c54f91d..1743388
Fast-forward
 Tugas-Php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Php.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasPHP"
On branch Tugas-php
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git add Tugas-Php.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git commit -m "tugasPHP"
[Tugas-php f8d271e] tugasPHP
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git status
On branch Tugas-php
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-php
Updating 1743388..f8d271e
Fast-forward
 Tugas-Php.txt | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 492 bytes | 123.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/FerlyMamoto/belajarGIT.git
   c54f91d..f8d271e  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git branch Tugas-finalProject

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-FinalProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.email "mamotoferly@gmail.com"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git config --global user.name "FerlyMamoto"

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git commit -m "tugasFinalProject"
[Tugas-finalProject 25b77d2] tugasFinalProject
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git status
On branch Tugas-finalProject
nothing to commit, working tree clean

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating f8d271e..25b77d2
Fast-forward
 Tugas-FinalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-FinalProject.txt

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 285 bytes | 142.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/FerlyMamoto/belajarGIT.git
   f8d271e..25b77d2  main -> main

HP@LAPTOP-G0QOR7P4 MINGW64 /c/GIT/belajarGIT (main)
$

