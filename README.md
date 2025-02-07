# portfolio1

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (master)ect 1 (master)
$ echo "# portfolio1" >> README.md

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (master)
$ git init
Reinitialized existing Git repository in C:/Users/Tassili/Desktop/html project 1/.git//Tassili/Desktop/html project 1/.git/
                                                 ect 1 (master)
Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (master)                                   ill be replaced by CRLF the next time Git touches it
$ git add README.md
warning: in the working copy of 'README.md', LF wect 1 (master)ill be replaced by CRLF the next time Git touches it

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (master)
$ git commit -m "first commit"
[master (root-commit) 57daa07] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 README.md

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (master)
$ git branch -M main

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git remote add origin https://github.com/houdasoso/portfolio1.git

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 225 bytes | 225.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/houdasoso/portfolio1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git remote add origin https://github.com/houdasoso/portfolio1.git
error: remote origin already exists.

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git branch -M main

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.    

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        7442cdec2fa90c5b384d34e8b3bc6384.jpg     
        portfolio1.html
        "t commit\357\200\242"
        videoplayback.mp3
        videoplayback.mp4

nothing added to commit but untracked files present (use "git add" to track)

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git add .
warning: in the working copy of 't commit', LF will be replaced by CRLF the next time Git touches it

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git commit -m "Add project files"
[main 8ad99f4] Add project files
 5 files changed, 83 insertions(+)
 create mode 100644 7442cdec2fa90c5b384d34e8b3bc6384.jpg
 create mode 100644 portfolio1.html
 create mode 100644 "t commit\357\200\242"       
 create mode 100644 videoplayback.mp3
 create mode 100644 videoplayback.mp4

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git push
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (7/7), done.
Writing objects:  85% (6/7), 984.00 KiB | 260.00 
Writing objects:  85% (6/7), 1.11 MiB | 259.00 KiWriting objects:  85% (6/7), 1.25 MiB | 238.00 KiWriting objects:  85% (6/7), 1.38 MiB | 215.00 KiWriting objects:  85% (6/7), 1.47 MiB | 209.00 KiWriting objects:  85% (6/7), 1.59 MiB | 190.00 KiWriting objects:  85% (6/7), 1.66 MiB | 184.00 KiWriting objects:  85% (6/7), 1.78 MiB | 111.00 KiWriting objects:  85% (6/7), 1.85 MiB | 99.00 KiBWriting objects:  85% (6/7), 1.93 MiB | 102.00 KiWriting objects:  85% (6/7), 2.05 MiB | 87.00 KiBWriting objects:  85% (6/7), 2.11 MiB | 87.00 KiBWriting objects:  85% (6/7), 2.17 MiB | 82.00 KiBWriting objects: 100% (7/7), 2.17 MiB | 82.00 KiBWriting objects: 100% (7/7), 2.19 MiB | 142.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/houdasoso/portfolio1.git
   57daa07..8ad99f4  main -> main

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git add .

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git commit -m "Added footer to the HTML page"
[main 2f80c5b] Added footer to the HTML page
 1 file changed, 9 insertions(+), 1 deletion(-)  

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 462 bytes | 462.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/houdasoso/portfolio1.git
   8ad99f4..2f80c5b  main -> main

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)
$

Houda@DESKTOP-S12MMM1 MINGW64 ~/Desktop/html project 1 (main)