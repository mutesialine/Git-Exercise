# Git Exercise
## bundle1
### Exercise1
```bash
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
 ```
 ### exercise2

 ```bash
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

```


## Bundle-2

### Exercise-1

```bash
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

```
 
 
  ### Exercise2

```bash 
TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git pull
Already up to date.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git commit -m "added service list"
[ft/service-redesign 8c7b62b] added service list
 1 file changed, 16 insertions(+)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 468 bytes | 468.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0        
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/service-redesign
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git  commit -m "new list of service"
[main 1de24d6] new list of service
 1 file changed, 17 insertions(+)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 476 bytes | 476.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mutesialine/Git-Exercise.git
   35e6279..1de24d6  main -> main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git merge main
Auto-merging service.html
CONFLICT (content): Merge conflict in service.html
Automatic merge failed; fix conflicts and then commit the result.

Merge branch 'main' into ft/service-redesign
TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign|MERGING)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign|MERGING)
$ git commit
[ft/service-redesign 1e65f86] Merge branch 'main' into ft/service-redesign

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/service-redesign)
$ git push origin  ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 392 bytes | 392.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/mutesialine/Git-Exercise.git
   8c7b62b..1e65f86  ft/service-redesign -> ft/service-redesign

```


## Bundle-3
### Exercise-1

```bash

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git add team.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git commit -m "new page of team"
[ft/team-page 5f3b57d] new page of team
 1 file changed, 13 insertions(+)
 create mode 100644 team.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 469 bytes | 117.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/team-page
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/team-page -> ft/team-page

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git log
commit 5f3b57df27212cb663072c61c9490bf8118838d4 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:06:17 2022 +0200

    new page of team

commit 4c002ce631886abe665c75571ff5378de2e38f87 (origin/main, origin/HEAD, main, ft/contact-page)
Author: Mutesi <ktesialine@gmail.com>
:...skipping...
commit 5f3b57df27212cb663072c61c9490bf8118838d4 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:06:17 2022 +0200

    new page of team

commit 4c002ce631886abe665c75571ff5378de2e38f87 (origin/main, origin/HEAD, main, ft/contact-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 11:33:08 2022 +0200

    bundele2 exercise2

commit 1de24d6684a35ff5b22ef6c9ab4079518ab2fa8f
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 10:14:02 2022 +0200
:...skipping...
commit 5f3b57df27212cb663072c61c9490bf8118838d4 (HEAD -> ft/team-page, origin/ft/team-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:06:17 2022 +0200

    new page of team

commit 4c002ce631886abe665c75571ff5378de2e38f87 (origin/main, origin/HEAD, main, ft/contact-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 11:33:08 2022 +0200

    bundele2 exercise2

commit 1de24d6684a35ff5b22ef6c9ab4079518ab2fa8f
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 10:14:02 2022 +0200

    new list of service

commit 35e6279386acca5457bc9abe4404650d6378aeac
Merge: 7f9190e 1035c2b
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Tue Oct 25 12:00:28 2022 +0200

    Merge pull request #1 from mutesialine/ft/bundle-2

    create service page

commit 7f9190ef918b2d9e21a74ad51295e5b493bd4af7
Author: Mutesi <ktesialine@gmail.com>
Date:   Tue Oct 25 08:54:37 2022 +0200

    bundle2 exercise1

commit 1035c2baff197e05ad800e154bf6b9a0931d3f78 (origin/ft/bundle-2)
Author: Mutesi <ktesialine@gmail.com>
Date:   Tue Oct 25 08:40:14 2022 +0200

    create service page

commit f93a1993e3913cfdd85d9366dd3d03d641b71b74
Author: Mutesi <ktesialine@gmail.com>
Date:   Mon Oct 24 10:02:25 2022 +0200

    Bundle1 exercise 2

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git cherry-pick 5f3b57df27212cb663072c61c9490bf8118838d4
[ft/contact-page 5b197e9] new page of team
 Date: Thu Oct 27 14:06:17 2022 +0200
 1 file changed, 13 insertions(+)
 create mode 100644 team.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git commit -m "contact pages"
[ft/contact-page f664ec8] contact pages
 1 file changed, 12 insertions(+)
 create mode 100644 contact.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 738 bytes | 369.00 KiB/s, done.
Total 6 (delta 3), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/contact-page
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/contact-page -> ft/contact-page

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git add faq.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git commit -m "faq page with some new content"
[ft/faq-page f3253d9] faq page with some new content
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 464 bytes | 154.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote: 
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/faq-page
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/faq-page -> ft/faq-page

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git log
commit f3253d9d469c85e1590dca79a0113d2889d12f38 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:48:19 2022 +0200

    faq page with some new content

:...skipping...
commit f3253d9d469c85e1590dca79a0113d2889d12f38 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:48:19 2022 +0200

    faq page with some new content

commit f664ec82c7d40c4ef138a8d21bee4dee6cfc0635 (origin/ft/contact-page, ft/contact-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:42:03 2022 +0200

    contact pages

commit 5b197e9f27b1214f5a97f22b15b995938fe5c702
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:06:17 2022 +0200
:...skipping...
commit f3253d9d469c85e1590dca79a0113d2889d12f38 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:48:19 2022 +0200
Revert "new page of team"

    faq page with some new content

commit f664ec82c7d40c4ef138a8d21bee4dee6cfc0635 (origin/ft/contact-page, ft/contact-page)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:42:03 2022 +0200

    contact pages

commit 5b197e9f27b1214f5a97f22b15b995938fe5c702
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 14:06:17 2022 +0200

    new page of team

commit 4c002ce631886abe665c75571ff5378de2e38f87 (origin/main, origin/HEAD, main)
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 11:33:08 2022 +0200

    bundele2 exercise2

commit 1de24d6684a35ff5b22ef6c9ab4079518ab2fa8f
Author: Mutesi <ktesialine@gmail.com>
Date:   Thu Oct 27 10:14:02 2022 +0200

    new list of service

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git revert 5b197e9f27b1214f5a97f22b15b995938fe5c702
[ft/faq-page 60accee] Revert "new page of team"
 1 file changed, 13 deletions(-)
 delete mode 100644 team.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 273 bytes | 273.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/mutesialine/Git-Exercise.git
   f3253d9..60accee  ft/faq-page -> ft/faq-page

```


### Exercise-2

```bash
TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/faq-page)
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git add .

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git commit -m "add home page content"
[main d92c824] add home page content
 1 file changed, 1 insertion(+)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 343 bytes | 68.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/mutesialine/Git-Exercise.git
   8820f44..d92c824  main -> main

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git add home.html

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git commit -m "add content2 on home page"
[ft/home-page-redesign a0a4df0] add content2 on home page
 1 file changed, 1 insertion(+)

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
fatal: unable to access 'https://github.com/mutesialine/Git-Exercise.git/': Could not resolve host: github.com

TheGym@DESKTOP-N5AF3JE MINGW64 ~/Git-Exercise (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 16, done.
Counting objects: 100% (16/16), done.
Delta compression using up to 4 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (14/14), 1.59 KiB | 815.00 KiB/s, done.
Total 14 (delta 7), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (7/7), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/mutesialine/Git-Exercise/pull/new/ft/home-page-redesign
remote:
To https://github.com/mutesialine/Git-Exercise.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign


 ```






