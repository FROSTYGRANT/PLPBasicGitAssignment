# PLPBasicGitAssignment
This is a PLP Sample Repo.

 Commands as in GIT BASH interface
$ cd c:/Users/ADMIN/Desktop/PLP/PLPBasicGitAssignment

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git init
Initialized empty Git repository in C:/Users/ADMIN/Desktop/PLP/PLPBasicGitAssignment/.git/

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git remote add origin https://github.com/FROSTYGRANT/PLPBasicGitAssignment.git

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git add hello.txt

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) 23603fa] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/FROSTYGRANT/PLPBasicGitAssignment.git'

ADMIN@DESKTOP-ILAVJH6 MINGW64 ~/Desktop/PLP/PLPBasicGitAssignment (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 242 bytes | 80.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/FROSTYGRANT/PLPBasicGitAssignment/pull/new/master
remote:
To https://github.com/FROSTYGRANT/PLPBasicGitAssignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
