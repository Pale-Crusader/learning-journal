This is where I am copy pasting the command prompt from going through the Git-Demo for future analysis.

### [Main Page](https://pale-crusader.github.io/learning-journal)

```C:\Users\Owner>cd Desktop

C:\Users\Owner\Desktop>cd projects

C:\Users\Owner\Desktop\projects>git clone https://pale-crusader.github.io/Git-De
mo/
Cloning into 'Git-Demo'...
fatal: repository 'https://pale-crusader.github.io/Git-Demo/' not found

C:\Users\Owner\Desktop\projects>git clone https://github.com/Pale-Crusader/Git-D
emo
Cloning into 'Git-Demo'...
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 593 bytes | 10.00 KiB/s, done.

C:\Users\Owner\Desktop\projects>cd git-demo

C:\Users\Owner\Desktop\projects\Git-Demo>cd .git

C:\Users\Owner\Desktop\projects\Git-Demo\.git>cd ..

C:\Users\Owner\Desktop\projects\Git-Demo>git remote -v
origin  https://github.com/Pale-Crusader/Git-Demo (fetch)
origin  https://github.com/Pale-Crusader/Git-Demo (push)

C:\Users\Owner\Desktop\projects\Git-Demo>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\Owner\Desktop\projects\Git-Demo>code .

C:\Users\Owner\Desktop\projects\Git-Demo>code .

C:\Users\Owner\Desktop\projects\Git-Demo>touch index.html

C:\Users\Owner\Desktop\projects\Git-Demo>git status
On branch master
Your branch is up to date with 'origin/master'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        CSS/
        index.html

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\Owner\Desktop\projects\Git-Demo>git add CSS .

C:\Users\Owner\Desktop\projects\Git-Demo>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   CSS/style.css
        new file:   index.html


C:\Users\Owner\Desktop\projects\Git-Demo>commit -m 'modified to test commiting'
'commit' is not recognized as an internal or external command,
operable program or batch file.

C:\Users\Owner\Desktop\projects\Git-Demo>git commit -m 'modified test commiting'

error: pathspec 'test' did not match any file(s) known to git
error: pathspec 'commiting'' did not match any file(s) known to git

C:\Users\Owner\Desktop\projects\Git-Demo>git commit -m "modified to test commiti
ng"
[master 7901b8c] modified to test commiting
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 CSS/style.css
 create mode 100644 index.html

C:\Users\Owner\Desktop\projects\Git-Demo>git push origin +master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 375 bytes | 187.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0)
To https://github.com/Pale-Crusader/Git-Demo
   6a44cc9..7901b8c  master -> master

C:\Users\Owner\Desktop\projects\Git-Demo>git fetch
remote: Enumerating objects: 5, done.
remote: Counting objects: 100% (5/5), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 820 bytes | 8.00 KiB/s, done.
From https://github.com/Pale-Crusader/Git-Demo
   7901b8c..f3654b0  master     -> origin/master

C:\Users\Owner\Desktop\projects\Git-Demo>git diff --cached index.html

C:\Users\Owner\Desktop\projects\Git-Demo>git diff origin/master
diff --git a/index.html b/index.html
index 7692003..e69de29 100644
--- a/index.html
+++ b/index.html
@@ -1,12 +0,0 @@
-<!DOCTYPE html>
-<html lang="en">
-<head>
-    <meta charset="UTF-8">
-    <meta name="viewport" content="width=100, initial-scale=1.0">
-    <meta http-equiv="X-UA-Compatible" content="ie=edge">
-    <title>Document</title>
-</head>
-<body>
-    <p>This is a Test</p>
-</body>
-</html>

C:\Users\Owner\Desktop\projects\Git-Demo>git pull origin master
From https://github.com/Pale-Crusader/Git-Demo
 * branch            master     -> FETCH_HEAD
Updating 7901b8c..f3654b0
Fast-forward
 index.html | 12 ++++++++++++
 1 file changed, 12 insertions(+)

C:\Users\Owner\Desktop\projects\Git-Demo>git add .

C:\Users\Owner\Desktop\projects\Git-Demo>git commit -m "quote to show after conf
lict"
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\Owner\Desktop\projects\Git-Demo>git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   CSS/style.css
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        second-page.html

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\Owner\Desktop\projects\Git-Demo>git add .

C:\Users\Owner\Desktop\projects\Git-Demo>git commit -m "this is a large change"
[master 10d270f] this is a large change
 3 files changed, 18 insertions(+), 1 deletion(-)
 create mode 100644 second-page.html

C:\Users\Owner\Desktop\projects\Git-Demo>git push origin +master
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 785 bytes | 52.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0)
To https://github.com/Pale-Crusader/Git-Demo
   f3654b0..10d270f  master -> master

C:\Users\Owner\Desktop\projects\Git-Demo>cd ..

C:\Users\Owner\Desktop\projects>git clone https://github.com/Pale-Crusader/learn
ing-journal
Cloning into 'learning-journal'...
remote: Enumerating objects: 103, done.
remote: Counting objects: 100% (103/103), done.
remote: Compressing objects: 100% (98/98), done.
Receiving objects:  14% (15/103remote: Total 103 (delta 46), reused 3 (delta 1),
 pack-reused 0
Receiving objects: 100% (103/103), 85.06 KiB | 1.06 MiB/s, done.
Resolving deltas: 100% (46/46), done.

C:\Users\Owner\Desktop\projects>ls
Git-Demo  learning-journal

C:\Users\Owner\Desktop\projects>cd learning-journal

C:\Users\Owner\Desktop\projects\learning-journal>ls
README.md  SetUp.PNG  _config.yml  learning-markdown.md  text-editor.md

C:\Users\Owner\Desktop\projects\learning-journal>git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

C:\Users\Owner\Desktop\projects\learning-journal>code .

C:\Users\Owner\Desktop\projects\learning-journal> 
```