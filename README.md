# training-git

# as owner
1. create repo on github
2. clone to local
9. as owner accept notif for pull request
10. owner ask the url of contributor repo for review update
11. owner clone the contributor repo with `git remote add [name] [contributor-url]`
12. after clone repo, owner check avilable local repo with `git remote -v` 
this check is usefull to check clone status success or failed
13. after that as owner make new branch to pull contributor repo for review and avoid new commit comein to master branch
with command `git branch [branch-name-for-review-contributor-commit]`
14. to check available branch can use this command `git branch`, active branch is mark with star (*) on the left
15. after check available branch, as owner checkout to branch for review contributor commit with 
command `git checkout [branch-name]`
16. before review contributor commit, owner must pull changes from contributor repo 
which already cloned and named in step 11, run with this command `git pull [name] [branch-name-of-contributor-repo]`
17. now branch of contributor ready to review




# as contributor
3. fork repo to contribut
4. clone repo to local with `git clone [url]`
5. add some file or edit file and show changes with `git status`
6. if any new files added, as contributor can add to git with `git add .` . 
if any files changed, as contributor can commit file to save changes into git with `git commit -m "update messages here"`
7. after that as contributor can push any commit or new file into git master with `git push`
8. as contributor notif to owner to pull contributor repo, as contributor can 
share this notif with social media or pull request on github

