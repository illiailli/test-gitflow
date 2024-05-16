# This is Git TEST 

Clone
```
git clone [Repository URL]
```

Add
```
git add .
```

Check - 
```
git status
```

Commit
```
git commit -m "[Message]"
```

Push
```
git push (origin [Branch]) 
```




Microsoft Windows [Version 10.0.20348.1129]
(c) Microsoft Corporation. All rights reserved.

C:\Users\Administrator\Documents\Workspace\test-gitflow>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Administrator\Documents\Workspace\test-gitflow>git add .

C:\Users\Administrator\Documents\Workspace\test-gitflow>git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


C:\Users\Administrator\Documents\Workspace\test-gitflow>git commit -m "(update)/readme"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Administrator@EV-CHQG3L42MMQ.(none)')

C:\Users\Administrator\Documents\Workspace\test-gitflow>git config user.email expresswebd3v@gmail.com

C:\Users\Administrator\Documents\Workspace\test-gitflow>git config user.name illiailli

C:\Users\Administrator\Documents\Workspace\test-gitflow>git config user.email expresswebd3v@gmail.com

C:\Users\Administrator\Documents\Workspace\test-gitflow>git commit -m "(update)/readme"
[main e3d8e57] (update)/readme
 1 file changed, 26 insertions(+), 1 deletion(-)

C:\Users\Administrator\Documents\Workspace\test-gitflow>git push origin
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 383 bytes | 383.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/illiailli/test-gitflow.git
   6da7ae2..e3d8e57  main -> main

C:\Users\Administrator\Documents\Workspace\test-gitflow>