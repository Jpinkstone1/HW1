Last login: Wed Nov  2 16:02:51 on ttys000
(base) jonathanpinkstone@Jonathans-MacBook-Pro ~ % git init
Reinitialized existing Git repository in /Users/jonathanpinkstone/.git/
(base) jonathanpinkstone@Jonathans-MacBook-Pro ~ % git add "Text1.md.txt"
fatal: pathspec 'Text1.md.txt' did not match any files
(base) jonathanpinkstone@Jonathans-MacBook-Pro ~ % cd desktop
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % git add "Text1.md.txt"
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % git commit -m "first commit"
[main e566419] first commit
 1 file changed, 1 insertion(+)
 create mode 100644 Desktop/Text1.md.txt
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % git branch -M main
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % git remote add origin https://github.com/Jpinkstone1/Homework1.git
error: remote origin already exists.
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % git push -u origin main 
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (6/6), 476 bytes | 476.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Jpinkstone1/HW1.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
(base) jonathanpinkstone@Jonathans-MacBook-Pro desktop % 
