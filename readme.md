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
