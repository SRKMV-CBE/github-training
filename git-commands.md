# Git Commands 

```sh
BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ git config --global user.name "Raghavan alias Saravanan Muthu"

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ git config --global user.email "raghavan*****@o****k.c**"

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ git config --global user.name
Raghavan alias Saravanan Muthu

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ git config --global user.email\
> ^C

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ git config --global user.email
raghavan*****@o****k.c**

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ pwd
/c/Users/BCA-LAB-30

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ mkdir git-projects

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~
$ cd git-projects/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ git clone git@github.com:itsraghz/my-first-repo.git
Cloning into 'my-first-repo'...
The authenticity of host 'github.com (20.207.73.82)' can't be established.
ED25519 key fingerprint is SHA256:+DiY3wvvV6TuJJhbpZisF/zLDA0zPMSvHdkr4UvCOqU.
This key is not known by any other names.
Are you sure you want to continue connecting (yes/no/[fingerprint])? yes
Warning: Permanently added 'github.com' (ED25519) to the list of known hosts.
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ git clone https://github.com/itsraghz/my-first-repo.git
Cloning into 'my-first-repo'...
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (5/5), done.

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ ls
my-first-repo/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ ls -l
total 4
drwxr-xr-x 1 BCA-LAB-30 197121 0 Jul  4 16:46 my-first-repo/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ ls -la
total 20
drwxr-xr-x 1 BCA-LAB-30 197121 0 Jul  4 16:46 ./
drwxr-xr-x 1 BCA-LAB-30 197121 0 Jul  4 16:42 ../
drwxr-xr-x 1 BCA-LAB-30 197121 0 Jul  4 16:46 my-first-repo/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects
$ cd my-first-repo/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls
LICENSE  README.md

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -l\
> ^C

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -l
total 9
-rw-r--r-- 1 BCA-LAB-30 197121 7048 Jul  4 16:46 LICENSE
-rw-r--r-- 1 BCA-LAB-30 197121   37 Jul  4 16:46 README.md

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -la
total 18
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 ./
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 ../
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 .git/
-rw-r--r-- 1 BCA-LAB-30 197121  290 Jul  4 16:46 .gitignore
-rw-r--r-- 1 BCA-LAB-30 197121 7048 Jul  4 16:46 LICENSE
-rw-r--r-- 1 BCA-LAB-30 197121   37 Jul  4 16:46 README.md

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -la
total 19
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 17:05 ./
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 ../
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 .git/
-rw-r--r-- 1 BCA-LAB-30 197121  290 Jul  4 16:46 .gitignore
-rw-r--r-- 1 BCA-LAB-30 197121 7048 Jul  4 16:46 LICENSE
-rw-r--r-- 1 BCA-LAB-30 197121   37 Jul  4 16:46 README.md
-rw-r--r-- 1 BCA-LAB-30 197121   21 Jul  4 17:05 test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        test.txt

nothing added to commit but untracked files present (use "git add" to track)

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git add test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   test.txt


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git commit -m "My First Commit"
[master c9c99f4] My First Commit
 1 file changed, 1 insertion(+)
 create mode 100644 test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git push
fatal: unable to access 'https://github.
com/itsraghz/my-first-repo.git/': Could
not resolve host: github.com

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git push
fatal: unable to access 'https://github.com/itsraghz/my-first-repo.git/': Could not resolv
e host: github.com

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git push
info: please complete authentication in your browser...
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 312 bytes | 312.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/itsraghz/my-first-repo.git
   59873be..c9c99f4  master -> master

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git history
git: 'history' is not a git command. See 'git --help'.

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log
commit c9c99f4cf4fd633d3174a8b6c39399f8b10b637d (HEAD -> master, origin/master, origin/HEA
D)
Author: Raghavan alias Saravanan Muthu <raghavan.muthu@outlook.com>
Date:   Tue Jul 4 17:14:27 2023 +0530

    My First Commit

commit 59873bea49f7e43e2375f6381294973228f5f446
Author: Raghavan alias Saravanan Muthu <raghavan.muthu@outlook.com>
Date:   Tue Jul 4 16:31:47 2023 +0530

    Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log --oneline
c9c99f4 (HEAD -> master, origin/master, origin/HEAD) My First Commit
59873be Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log --oneline
c9c99f4 (HEAD -> master, origin/master, origin/HEAD) My First Commit
59873be Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 714 bytes | 6.00 KiB/s, done.
From https://github.com/itsraghz/my-first-repo
   c9c99f4..313f004  master     -> origin/master

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git pull
Updating c9c99f4..313f004
Fast-forward
 test.txt | 1 +
 1 file changed, 1 insertion(+)

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log --oneline
313f004 (HEAD -> master, origin/master, origin/HEAD) Update test.txt
c9c99f4 My First Commit
59873be Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi HelloWorld.java

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -la
total 20
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 17:57 ./
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 16:46 ../
drwxr-xr-x 1 BCA-LAB-30 197121    0 Jul  4 17:51 .git/
-rw-r--r-- 1 BCA-LAB-30 197121  290 Jul  4 16:46 .gitignore
-rw-r--r-- 1 BCA-LAB-30 197121  113 Jul  4 17:57 HelloWorld.java
-rw-r--r-- 1 BCA-LAB-30 197121 7048 Jul  4 16:46 LICENSE
-rw-r--r-- 1 BCA-LAB-30 197121   37 Jul  4 16:46 README.md
-rw-r--r-- 1 BCA-LAB-30 197121   59 Jul  4 17:50 test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ javac HelloWorld.java
bash: javac: command not found

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ /c/Program
Program Files/       Program Files (x86)/ ProgramData/

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ /c/Program\ Files\ \(x86\)/Java/jdk1.7/bin/javac.exe  HelloWorld.java

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls -l
total 12
-rw-r--r-- 1 BCA-LAB-30 197121  426 Jul  4 17:58 HelloWorld.class
-rw-r--r-- 1 BCA-LAB-30 197121  113 Jul  4 17:57 HelloWorld.java
-rw-r--r-- 1 BCA-LAB-30 197121 7048 Jul  4 16:46 LICENSE
-rw-r--r-- 1 BCA-LAB-30 197121   37 Jul  4 16:46 README.md
-rw-r--r-- 1 BCA-LAB-30 197121   59 Jul  4 17:50 test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.java

nothing added to commit but untracked files present (use "git add" to track)

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git add .

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   HelloWorld.java


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi .gitignore

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   HelloWorld.java

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        HelloWorld.class


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ vi .gitignore

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   HelloWorld.java


BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git add .

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git commit -m "HelloWorld.java added"
[master b5f23a3] HelloWorld.java added
 1 file changed, 7 insertions(+)
 create mode 100644 HelloWorld.java

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log --oneline
b5f23a3 (HEAD -> master) HelloWorld.java added
313f004 (origin/master, origin/HEAD) Update test.txt
c9c99f4 My First Commit
59873be Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git push
To https://github.com/itsraghz/my-first-repo.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/itsraghz/my-first-repo.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 674 bytes | 4.00 KiB/s, done.
From https://github.com/itsraghz/my-first-repo
   313f004..2095920  master     -> origin/master
Merge made by the 'ort' strategy.
 dummy.text | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 dummy.text

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git log --oneline
b14fa16 (HEAD -> master) Merge branch 'master' of https://github.com/itsraghz/my-first-rep
o
2095920 (origin/master, origin/HEAD) Create dummy.text
b5f23a3 HelloWorld.java added
313f004 Update test.txt
c9c99f4 My First Commit
59873be Initial commit

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 654 bytes | 654.00 KiB/s, done.
Total 5 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/itsraghz/my-first-repo.git
   2095920..b14fa16  master -> master

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ git pull
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Compressing objects: 100% (1/1), done.
remote: Total 2 (delta 1), reused 1 (delta 1), pack-reused 0
Unpacking objects: 100% (2/2), 607 bytes | 20.00 KiB/s, done.
From https://github.com/itsraghz/my-first-repo
   b14fa16..b0b1420  master     -> origin/master
Updating b14fa16..b0b1420
Fast-forward
 dummy.text | 1 -
 1 file changed, 1 deletion(-)
 delete mode 100644 dummy.text

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$ ls
HelloWorld.class  HelloWorld.java  LICENSE  README.md  test.txt

BCA-LAB-30@DESKTOP-QQUR5DM MINGW64 ~/git-projects/my-first-repo (master)
$
```
