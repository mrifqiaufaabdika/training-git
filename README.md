# training-git
# contribution tutorial

# as owner
1 . create repo on github<br>
2 . clone to local<br>
9 . as owner accept notif for pull request<br>
10 . owner ask the url of contributor repo for review update<br>
11 . owner clone the contributor repo with `git remote add [name] [contributor-url]`<br>
12 . after clone repo, owner check avilable local repo with `git remote -v` this check is usefull to check clone status success or failed<br>
13 . after that as owner make new branch to pull contributor repo for review and avoid new commit comein to master branch with command `git branch [branch-name-for-review-contributor-commit]`<br>
14 . to check available branch can use this command `git branch`, active branch is mark with star (*) on the left<br>
15 . after check available branch, as owner checkout to branch for review contributor commit with command `git checkout [branch-name]`<br>
16 . before review contributor commit, owner must pull changes from contributor repo which already cloned and named in step 11, run with this command `git pull [name] [branch-name-of-contributor-repo]`<br>
17 . now branch of contributor ready to review<br>
18 . if code is must revision as owner notif to contributor for revision<br>
23 . as owner accept notif from contributor to pull commit<br>
24 . as owner check current branch for avoid wrong pulling branch, check current branch with command `git branch`<br>
25 . now if current branch is true, as owner pull commit from contributro repo, with this command `git pull [name] [branch-name]`<br>
26 . owner review code after pull commit, if 'OK' as owner checkout to master branch with this command `git checkout master`<br>
27 . ok, current branch is master. as owner check git status for check any new or changed file with this command `git status`<br>
28 . if status is ok mean no new of changed file, as owner merge branch master with review branch, merge with this command `git merge [review-branch-name]`<br>
29 . after merge ok, now as owner push commit into git with this command `git push`<br>
30 . mission completed<br>


# as contributor
3 . fork repo to contribut<br>
4 . clone repo to local with `git clone [url]`<br>
5 . add some file or edit file and show changes with `git status`<br>
6 . if any new files added, as contributor can add to git with `git add .` . if any files changed, as contributor can commit file to save changes into git with `git commit -m "update messages here"`<br>
7 . after that as contributor can push any commit or new file into git master with `git push`<br>
8 . as contributor notif to owner to pull contributor repo, as contributor can share this notif with social media or pull request on github<br>
19 . as contributor accept notif from owner to revision<br>
20 . contributor make revision and commit with command `git add . && git commit -m "update messages here"`<br>
21 . after that contributor push into contributor git master with command `git push`<br>
22 . as contributor send notif to owner for pull commit<br>
