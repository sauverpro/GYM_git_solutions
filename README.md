# *GIT EXERCISES SOLUTIONS*

## Bundel 1

# Exercise 1 || Solution

``` bash

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (master)
$ git branch -M main

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html

nothing added to commit but untracked files present (use "git add" to track)

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git add .
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git commit -m "this the main index "
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
[main (root-commit) 34e5cb9] this the main index
 1 file changed, 12 insertions(+)
 create mode 100644 index.html

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch main
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git remote add origin https://github.com/sauverpro/GYM_git_solutions.git

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git push -u origin main
fatal: unable to access 'https://github.com/sauverpro/GYM_git_solutions.git/': Could not resolve host: github.com

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 420 bytes | 2.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/sauverpro/GYM_git_solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (main)
$ git checkout -b dev
Switched to a new branch 'dev'

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git git push
git: 'git' is not a git command. See 'git --help'.

The most similar command is
        init

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev


SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git push --set-upstream origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/sauverpro/GYM_git_solutions/pull/new/dev
remote:
To https://github.com/sauverpro/GYM_git_solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git checkout -b test
Switched to a new branch 'test'

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (test)
$ git status
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
On branch test
nothing to commit, working tree clean

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (test)
$ git push origin test
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/sauverpro/GYM_git_solutions/pull/new/test
remote:
To https://github.com/sauverpro/GYM_git_solutions.git
 * [new branch]      test -> test

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (test)
$ git chechout dev
git: 'chechout' is not a git command. See 'git --help'.

The most similar command is
        checkout

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (test)
$ git checkout dev
hint: core.useBuiltinFSMonitor=true is deprecated;please set core.fsmonitor=true instead
hint: Disable this message with "git config advice.useCoreFSMonitorConfig false"
Switched to branch 'dev'
Your branch is up to date with 'origin/dev'.

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git branch -D test
Deleted branch test (was 34e5cb9).

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git push origin --delete test
fatal: unable to access 'https://github.com/sauverpro/GYM_git_solutions.git/': OpenSSL SSL_read: Connection was reset, errno 10054

SauvePro@SauverPro MINGW64 /e/ojemba/git/GYM_git_solutions (dev)
$ git push origin --delete test
To https://github.com/sauverpro/GYM_git_solutions.git
 - [deleted]         test

```
## Exercise 2 || Solution

```bash


```