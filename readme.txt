git init // create repos
git add index.html // add specific
git add . // add all files
git commit -m "Version control message" //commit
git commit -a -m "Version control message" //add + commit

git status
git diff //unstaged changes
git diff --staged //staged changes

git branch mybranch //create a branch
git branch -d mybranch //delete a branch
git checkout mybranch //change to a branch
git checkout -b mybranch //create and change to a branch

// add remote site
git remote add origin https://github.com/fphivedev/gitbasics.git // origin is default
git push -u origin master // default and current branch


[esc]:wq - to save and get out of vim