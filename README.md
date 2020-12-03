*Música maestro*

**Exámen GitHub**

History:

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git config --global user.name DaniellTec

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git config --global user.email danieltecpuhawan@gmail.com

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git config --global user.password

Alumno@PC15524 MINGW64 ~/Desktop
$ git clone https://github.com/DaniellTec/repoNotas.git
Cloning into 'repoNotas'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 592 bytes | 148.00 KiB/s, done.

Alumno@PC15524 MINGW64 ~/Desktop
$ dir repoNotas
README.md

Alumno@PC15524 MINGW64 ~/Desktop
$ git add *.txt
fatal: not a git repository (or any of the parent directories): .git

Alumno@PC15524 MINGW64 ~/Desktop
$ cd repoNotas

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git add *.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git commit -m "Notas Musicales"
[main 8fee921] Notas Musicales
 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 do.txt
 create mode 100644 fa.txt
 create mode 100644 mi.txt
 create mode 100644 re.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git log
commit 8fee921bc3a44af5fc129aa3c83f9594d6803c01 (HEAD -> main)
Author: DaniellTec <danieltecpuhawan@gmail.com>
Date:   Thu Dec 3 15:03:06 2020 +0100

    Notas Musicales

commit 4515236a57588b056bf8252a6210db2ee00321c1 (origin/main, origin/HEAD)
Author: DaniellTec <73247445+DaniellTec@users.noreply.github.com>
Date:   Thu Dec 3 15:01:37 2020 +0100

    Initial commit

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git log --graph --decorate --pretty=oneline
* 8fee921bc3a44af5fc129aa3c83f9594d6803c01 (HEAD -> main) Notas Musicales
* 4515236a57588b056bf8252a6210db2ee00321c1 (origin/main, origin/HEAD) Initial commit

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git tag notasMusicales

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git tag -m
error: switch `m' requires a value

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git tag -l
notasMusicales

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git status
On branch main
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git log
commit 8fee921bc3a44af5fc129aa3c83f9594d6803c01 (HEAD -> main, tag: notasMusicales)
Author: DaniellTec <danieltecpuhawan@gmail.com>
Date:   Thu Dec 3 15:03:06 2020 +0100

    Notas Musicales

commit 4515236a57588b056bf8252a6210db2ee00321c1 (origin/main, origin/HEAD)
Author: DaniellTec <73247445+DaniellTec@users.noreply.github.com>
Date:   Thu Dec 3 15:01:37 2020 +0100

    Initial commit

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git log --graph --decorate --pretty=oneline
* 8fee921bc3a44af5fc129aa3c83f9594d6803c01 (HEAD -> main, tag: notasMusicales) Notas Musicales
* 4515236a57588b056bf8252a6210db2ee00321c1 (origin/main, origin/HEAD) Initial commit

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 298 bytes | 298.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DaniellTec/repoNotas.git
   4515236..8fee921  main -> main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch claveSol

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch claveFa

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch sostenido

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/DaniellTec/repoNotas.git/'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git add sol.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git commit -m "Notas Musicales"
[main 305f8a4] Notas Musicales
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 sol.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git add la.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git commit -m "Notas Musicales"
[main b5c57ca] Notas Musicales
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 la.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 465 bytes | 465.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/DaniellTec/repoNotas.git
   8fee921..b5c57ca  main -> main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git pull
Already up to date.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch
  claveFa
  claveSol
* main
  sostenido

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git checkout claveFa
Switched to branch 'claveFa'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveFa)
$ git push
fatal: The current branch claveFa has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin claveFa


Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveFa)
$ git push --set-upstream origin claveFa
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/DaniellTec/repoNotas.git/'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveFa)
$ git push --set-upstream origin claveFa
Logon failed, use ctrl+c to cancel basic credential prompt.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'claveFa' on GitHub by visiting:
remote:      https://github.com/DaniellTec/repoNotas/pull/new/claveFa
remote:
To https://github.com/DaniellTec/repoNotas.git
 * [new branch]      claveFa -> claveFa
Branch 'claveFa' set up to track remote branch 'claveFa' from 'origin'.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveFa)
$ git checkout claveSol
Switched to branch 'claveSol'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveSol)
$ git push --set-upstream origin claveSol
Logon failed, use ctrl+c to cancel basic credential prompt.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'claveSol' on GitHub by visiting:
remote:      https://github.com/DaniellTec/repoNotas/pull/new/claveSol
remote:
12962267 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
13777726 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
14167998 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
14339981 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
14496072 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
14633283 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
14808625 [sig] bash 1692! sigpacket::process: Suppressing signal 18 to win32 process (pid 6148)
Merge made by the 'recursive' strategy.
 la.txt  | 0
 sol.txt | 0
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 la.txt
 create mode 100644 sol.txt

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git pull
Already up to date.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/DaniellTec/repoNotas.git/'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 237 bytes | 237.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/DaniellTec/repoNotas.git
   12a6136..5e44c6a  main -> main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch -d claveFa
Deleted branch claveFa (was 8fee921).

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch
  claveSol
* main
  sostenido

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch -m sostenido claveDo

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch
  claveDo
  claveSol
* main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git branch claveDo
fatal: A branch named 'claveDo' already exists.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git checkout claveDo
Switched to branch 'claveDo'
Your branch is up to date with 'origin/sostenido'.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git push
fatal: The upstream branch of your current branch does not match
the name of your current branch.  To push to the upstream branch
on the remote, use

    git push origin HEAD:sostenido

To push to the branch of the same name on the remote, use

    git push origin HEAD

To choose either option permanently, see push.default in 'git help config'.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git push --set-upstream origin claveDo
Logon failed, use ctrl+c to cancel basic credential prompt.
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'claveDo' on GitHub by visiting:
remote:      https://github.com/DaniellTec/repoNotas/pull/new/claveDo
remote:
To https://github.com/DaniellTec/repoNotas.git
 * [new branch]      claveDo -> claveDo
Branch 'claveDo' set up to track remote branch 'claveDo' from 'origin'.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git branch
* claveDo
  claveSol
  main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git pull
Already up to date.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git log
commit 8fee921bc3a44af5fc129aa3c83f9594d6803c01 (HEAD -> claveDo, tag: notasMusicales, origin/sostenido, origin/claveFa, origin/claveDo)
Author: DaniellTec <danieltecpuhawan@gmail.com>
Date:   Thu Dec 3 15:03:06 2020 +0100

    Notas Musicales

commit 4515236a57588b056bf8252a6210db2ee00321c1
Author: DaniellTec <73247445+DaniellTec@users.noreply.github.com>
Date:   Thu Dec 3 15:01:37 2020 +0100

    Initial commit

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git status
On branch claveDo
Your branch is up to date with 'origin/claveDo'.

nothing to commit, working tree clean

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (claveDo)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ nano README.md

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ nano README.md

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ nano README.md

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ nano README.md

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Everything up-to-date

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git add -A README.md
warning: LF will be replaced by CRLF in README.md.
The file will have its original line endings in your working directory

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git add -A README.md

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git commit -m "ReadMe"
[main 58be13b] ReadMe
 1 file changed, 6 insertions(+), 1 deletion(-)

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/DaniellTec/repoNotas.git/'

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$ git push
Logon failed, use ctrl+c to cancel basic credential prompt.
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 322 bytes | 322.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/DaniellTec/repoNotas.git
   5e44c6a..58be13b  main -> main

Alumno@PC15524 MINGW64 ~/Desktop/repoNotas (main)
$


