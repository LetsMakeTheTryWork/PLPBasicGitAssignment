Microsoft Windows [Version 10.0.22621.3880]
(c) Microsoft Corporation. All rights reserved.

C:\Users\admin>git --version
git version 2.46.0.windows.1

C:\Users\admin>cd C:\Users\admin\Desktop\PLPBasicGitAssignment

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git init
Initialized empty Git repository in C:/Users/admin/Desktop/PLPBasicGitAssignment/.git/

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir /a
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:30    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  02:30    <DIR>          .git
               0 File(s)              0 bytes
               3 Dir(s)  62,655,156,224 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git
'https:' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>git remote add origin https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git

C:\Users\admin\Desktop\PLPBasicGitAssignment>git remote -v
origin  https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git (fetch)
origin  https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git (push)

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add .

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@DESKTOP-E1CVKMP.(none)')

C:\Users\admin\Desktop\PLPBasicGitAssignment>echo "Hello, Git!" > hello.txt
Access is denied.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Add hello.txt with a greeting message"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@DESKTOP-E1CVKMP.(none)')

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


C:\Users\admin\Desktop\PLPBasicGitAssignment>git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git'

C:\Users\admin\Desktop\PLPBasicGitAssignment>git branch

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git push --set-upstream origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git'

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push --set-upstream origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git'

C:\Users\admin\Desktop\PLPBasicGitAssignment>git branch

C:\Users\admin\Desktop\PLPBasicGitAssignment>git log
fatal: your current branch 'master' does not have any commits yet

C:\Users\admin\Desktop\PLPBasicGitAssignment>git init
Reinitialized existing Git repository in C:/Users/admin/Desktop/PLPBasicGitAssignment/.git/

C:\Users\admin\Desktop\PLPBasicGitAssignment># Initial Commit
'#' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>This is the first commit to the repository.
'This' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md
fatal: pathspec 'README.md' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:42    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  02:43    <DIR>          hello.txt
               0 File(s)              0 bytes
               3 Dir(s)  62,653,485,056 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:55    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  02:55    <DIR>          README.md
               0 File(s)              0 bytes
               3 Dir(s)  62,651,789,312 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md

C:\Users\admin\Desktop\PLPBasicGitAssignment>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:55    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  02:55    <DIR>          README.md
               0 File(s)              0 bytes
               3 Dir(s)  62,651,199,488 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md

C:\Users\admin\Desktop\PLPBasicGitAssignment>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md

C:\Users\admin\Desktop\PLPBasicGitAssignment>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md/SoftwareAssign.txt.docx


C:\Users\admin\Desktop\PLPBasicGitAssignment>git init
Reinitialized existing Git repository in C:/Users/admin/Desktop/PLPBasicGitAssignment/.git/

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@DESKTOP-E1CVKMP.(none)')

C:\Users\admin\Desktop\PLPBasicGitAssignment>git remote add origin https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git
error: remote origin already exists.

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push -u origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git'

C:\Users\admin\Desktop\PLPBasicGitAssignment>git branch

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git checkout -b master
Switched to a new branch 'master'

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Initial commit"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'admin@DESKTOP-E1CVKMP.(none)')

C:\Users\admin\Desktop\PLPBasicGitAssignment>git log
fatal: your current branch 'master' does not have any commits yet

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --global user.name "Your Name"

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --global user.email "your-email@example.com"

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --global user.name "Bett" git config --global user.email "your-beshbetty21@gmail.com"
error: no action specified

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --global user.name "Bett"

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --global user.email "your-beshbetty21@gmail.com"

C:\Users\admin\Desktop\PLPBasicGitAssignment>git config --list
diff.astextplain.textconv=astextplain
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true
http.sslbackend=openssl
http.sslcainfo=C:/Program Files/Git/mingw64/etc/ssl/certs/ca-bundle.crt
core.autocrlf=true
core.fscache=true
core.symlinks=false
pull.rebase=false
credential.helper=manager
credential.https://dev.azure.com.usehttppath=true
init.defaultbranch=master
user.name=Bett
user.email=your-beshbetty21@gmail.com
core.repositoryformatversion=0
core.filemode=false
core.bare=false
core.logallrefupdates=true
core.symlinks=false
core.ignorecase=true
remote.origin.url=https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add README.md

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Initial commit"
[master (root-commit) 9ee1187] Initial commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md/SoftwareAssign.txt.docx

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push -u origin master
fatal: User cancelled dialog.
Username for 'https://github.com':
Password for 'https://github.com':
remote: No anonymous write access.
fatal: Authentication failed for 'https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git/'

C:\Users\admin\Desktop\PLPBasicGitAssignment> Committing Changes:
'Committing' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>  - Stage the changes.
'-' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   ```bash
'```bash' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   ```
'```' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>  - Commit the changes.
'-' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   ```bash
'```bash' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   git commit -m "Add hello.txt with a greeting"
On branch master
nothing to commit, working tree clean

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>   ```
'```' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:55    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  03:04    <DIR>          README.md
               0 File(s)              0 bytes
               3 Dir(s)  62,642,155,520 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>ls
'ls' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  02:55    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  03:17    <DIR>          README.md
               0 File(s)              0 bytes
               3 Dir(s)  62,671,433,728 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>dir
 Volume in drive C is 系统
 Volume Serial Number is BD90-89A1

 Directory of C:\Users\admin\Desktop\PLPBasicGitAssignment

31/07/2024  03:18    <DIR>          .
31/07/2024  01:24    <DIR>          ..
31/07/2024  03:16           222,992 hello.txt.docx
31/07/2024  03:18    <DIR>          README.md
               1 File(s)        222,992 bytes
               3 Dir(s)  62,672,609,280 bytes free

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt
fatal: pathspec 'hello.txt' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt.dox
fatal: pathspec 'hello.txt.dox' did not match any files

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add hello.txt.docx

C:\Users\admin\Desktop\PLPBasicGitAssignment>git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   hello.txt.docx


C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Add hello.txt.docx with a greeting"
[master 3ae9a66] Add hello.txt.docx with a greeting
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 hello.txt.docx

C:\Users\admin\Desktop\PLPBasicGitAssignment>git log
commit 3ae9a665eac16de3624b0ba0bfecb0d1f1dd833c (HEAD -> master)
Author: Bett <your-beshbetty21@gmail.com>
Date:   Wed Jul 31 03:20:48 2024 +0300

    Add hello.txt.docx with a greeting

commit 9ee1187a3d4825e4bbe1c76a3985b975a6fb622e
Author: Bett <your-beshbetty21@gmail.com>
Date:   Wed Jul 31 03:12:07 2024 +0300

    Initial commit

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


C:\Users\admin\Desktop\PLPBasicGitAssignment>git push --set-upstream origin master
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (7/7), 315.62 KiB | 9.02 MiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/LetsMakeTheTryWork/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment>git branch -r
  origin/master

C:\Users\admin\Desktop\PLPBasicGitAssignment>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\admin\Desktop\PLPBasicGitAssignment>git add .

C:\Users\admin\Desktop\PLPBasicGitAssignment>git commit -m "Your commit message"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\admin\Desktop\PLPBasicGitAssignment>git push
Everything up-to-date

C:\Users\admin\Desktop\PLPBasicGitAssignment>
C:\Users\admin\Desktop\PLPBasicGitAssignment># PLPBasicGitAssignment
This repository is for the PLP Basic Git assignment.
