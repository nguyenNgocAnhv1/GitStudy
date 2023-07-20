# create a new git repository
git init

# get a repository
git clone hppts://

# push to a branch
git push origin tenbranch

# Ignore file or folder by name. Insert file name to .gitignore
.gitignore

# check status
git status

# add all 
git add *

# add file by name
git add tenfile 

# commit file
git commit-m ""

# show commit change (the changes in last commit )
git show ff2da4c83847638d1c90937644b43328dc8e7a5e1

# show history commits
git log

# show details of changes
git diff (the changing now)

# GUI to show changes
gitk

# Delete changes file not in the current stage
git checkout -- filename

# Unstage 
git restore --staged filename
git reset filename

# new branch
git branch namebranch

# show all branches 
git branch

# changes branch
git checkout namebranch

# merge branch
- git merge namebranch
- reset file to specify commmit
git reset --soft id_commit      (Uncommit) 
git reset --mixed id_commit     (Uncommit + Unstage)
git reset --hard id_commit      (Uncommit + Unstage + Delete)

# switch to a commit 
git switch cf48daa60768153065c4e7a83d753e35fe8dcd51 --detach









-- Revert the changes in the other commit ( not delete commits above this) 
--xóa những thay đổi ở 1 commit trước đó tuy nhiên sẽ không xóa những commit phía trên mà sẽ tạo ra thêm 1 commit mới
git revert tencommit
-- Ignore file or folder by name. Insert file name to .gitignore
.gitignore
