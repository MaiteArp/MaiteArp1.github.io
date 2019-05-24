## Friday 17th ## 

[README](./README.md)
[monday](./monday.md)
[wednesday15](./wednesday15.md)
[saturdayhtml](./saturdayhtml.md)
[saturdaycss](./saturdaycss.md)
[saturdayjs](./saturdayjs.md)
[monday20](./monday20.md)
[wednesday22](./wednesday22.md)
[learned](./learned.md)

All about git 

Maite$ pwd
/mnt/c/Users/Maite
Maite$ cd projects/
**projects$ git clone https://github.com/MaiteArp/MaiteArp1.github.io.git**
Cloning into 'MaiteArp1.github.io'...
remote: Enumerating objects: 26, done.
remote: Counting objects: 100% (26/26), done.
remote: Compressing objects: 100% (24/24), done.
remote: Total 26 (delta 6), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (26/26), done.
projects$ ls
 DoubleP1     MaiteArp1.github.io   OwlandFox.html   Wrdsearch.jpg   indexstyle.css     wolf.jpg
 Index.html   OLd                   Project1         index.js       'wolf - Copy.jpg'
projects$ cd MaiteArp1.github.io/
**MaiteArp1.github.io[master]$ ls**
README.md  _config.yml
**MaiteArp1.github.io[master]$ code .**
git status
**^C**
**MaiteArp1.github.io[master]$ git status**
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean
MaiteArp1.github.io[master]$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")
MaiteArp1.github.io[master !]$ git add --all
MaiteArp1.github.io[master !]$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.md

**MaiteArp1.github.io[master !]$ git commit -m "added date"**
[master 8ae5e80] added date
 1 file changed, 2 insertions(+)
MaiteArp1.github.io[master *]$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
**MaiteArp1.github.io[master *]$ git push origin master**
Username for 'https://github.com': MaiteArp
Password for 'https://MaiteArp@github.com':
remote: Invalid username or password.
fatal: Authentication failed for 'https://github.com/MaiteArp/MaiteArp1.github.io.git/'
MaiteArp1.github.io[master *]$ git push origin master
Username for 'https://github.com': MaiteArp
Password for 'https://MaiteArp @github.com':
Counting objects: 3, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 322 bytes | 161.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/MaiteArp/MaiteArp1.github.io.git
   ca9cadb..8ae5e80  master -> master

