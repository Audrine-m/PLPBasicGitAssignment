# PLPBasicGitAssignment
Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ cd "C:\Users\Audrine\Documents\PLPBasicGitAssignment"

Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ git init
Reinitialized existing Git repository in C:/Users/Audrine/Documents/PLPBasicGitAssignment/.git/

Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ git remote add origin https://github.com/Audrine-m/PLPBasicGitAssignment.git
error: remote origin already exists.

Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ touch hello.txt

Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ echo Hello, Git
Hello, Git
Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ git add hello.txt
Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ git commit -m "Add hello.txt with a greeting"
On branch main
Your branch is up to date with 'origin/master'.
nothing to commit, working tree clean
Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$ git push -u origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 582 bytes | 582.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/Audrine-m/PLPBasicGitAssignment.git
   861a586..f32669b  main -> main
branch 'main' set up to track 'origin/main'.

Audrine@DESKTOP-DHG6RKM MINGW64 ~/Documents/PLPBasicGitAssignment (main)
$

