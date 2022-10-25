# Git Exercise
## bundle1
### Exercise1
...bash
TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise
$ git init
Initialized empty Git repository in C:/Users/TheGym/Git-Exercise/.git/

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git branch -M main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add readme.md

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git commit -m "init project"
On branch main
nothing to commit, working tree clean

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git remote add origin https://github.com/mutesialine/Git-Exercise.git
error: remote origin already exists.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/dev
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      dev -> dev

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/test
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      test -> test

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git branch dev
fatal: a branch named 'dev' already exists

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git checkout dev
Switched to branch 'dev'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git branch -D test
Deleted branch test (was 1cf68ec).

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git push origin --delete test
To https://github.com/mutesialine/Git-Exercise.git
 - [deleted]         test
 ...
 ### exercise2
 ...bash
 TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise
$ git init
Initialized empty Git repository in C:/Users/TheGym/Git-Exercise/.git/

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git branch -M Master

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Master)
$ git branch -M Main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git add readme.md

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git status
On branch Main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   readme.md


TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git commit -m "init project"
[Main (root-commit) 1cf68ec] init project
 1 file changed, 1 insertion(+)
 create mode 100644 readme.md

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git remote add origin https://github.com/mutesialine/Git-Exercise.git

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git push -u origin main
fatal: main cannot be resolved to branch

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git branch -m main
fatal: a branch named 'main' already exists

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git branch main
fatal: a branch named 'main' already exists

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (Main)
$ git branch -M main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add readme.md

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git commit -m "init project"
On branch main
nothing to commit, working tree clean

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git remote add origin https://github.com/mutesialine/Git-Exercise.git
error: remote origin already exists.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b dev
Switched to a new branch 'dev'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git push origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/dev
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      dev -> dev

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git checkout -b test
Switched to a new branch 'test'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/test
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      test -> test

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git branch dev
fatal: a branch named 'dev' already exists

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (test)
$ git checkout dev
Switched to branch 'dev'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git branch -D test
Deleted branch test (was 1cf68ec).

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git push origin --delete test
To https://github.com/mutesialine/Git-Exercise.git
 - [deleted]         test

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (dev)
$ git checkout main
Switched to branch 'main'
M       readme.md
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git commit -m "bundle1 exercise1"
[main 5552a0f] bundle1 exercise1
 1 file changed, 73 insertions(+), 1 deletion(-)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 905 bytes | 452.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/mutesialine/Git-Exercise.git
   1cf68ec..5552a0f  main -> main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add home.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash
Saved working directory and index state WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add about.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash
Saved working directory and index state WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add team.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash
Saved working directory and index state WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash list
stash@{0}: WIP on main: 5552a0f bundle1 exercise1
stash@{1}: WIP on main: 5552a0f bundle1 exercise1
stash@{2}: WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (60836580d53d09a514514ca5fc0be04c28a55346)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash list
stash@{0}: WIP on main: 5552a0f bundle1 exercise1
stash@{1}: WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash stash@{1}
fatal: unknown subcommand: stash@{1}

usage: git stash list [<options>]
   or: git stash show [<options>] [<stash>]
   or: git stash drop [-q|--quiet] [<stash>]
   or: git stash ( pop | apply ) [--index] [-q|--quiet] [<stash>]
   or: git stash branch <branchname> [<stash>]
   or: git stash clear
   or: git stash [push [-p|--patch] [-S|--staged] [-k|--[no-]keep-index] [-q|--quiet]
                 [-u|--include-untracked] [-a|--all] [-m|--message <message>]
                 [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]]
   or: git stash save [-p|--patch] [-S|--staged] [-k|--[no-]keep-index] [-q|--quiet]
                 [-u|--include-untracked] [-a|--all] [<message>]


TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash pop stash@{1}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (a200541834a5bb7c2250e27c47998eff5ccdbbf8)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html


TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git commit -m"setup home and about page"
[main c27c092] setup home and about page
 2 files changed, 24 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 572 bytes | 286.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/mutesialine/Git-Exercise.git
   5552a0f..c27c092  main -> main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash list
stash@{0}: WIP on main: 5552a0f bundle1 exercise1

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git stash pop stash@{0}
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (f14bc1afd7528daeeae3d0373a8ad3b0486f259e)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git reset --hard
HEAD is now at c27c092 setup home and about page
...

## Bundle-2

### exercise1

...bash
TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/bundle-2)
$ git add service.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/bundle-2)
$ git commit -m"create service page"
[ft/bundle-2 1035c2b] create service page
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 service.html

 TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 273 bytes | 136.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/bundle-2
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

 ...


