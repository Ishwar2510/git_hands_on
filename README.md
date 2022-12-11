git init
echo >> README.md
git add .
git commit -m 'first commit'
git branch -M main
git remote add origin linkname
git push -u origin main
git branch newbranchname
git checkout newbranchname
or 
git checkout -b newbranchname
git branch
git log
git checkout branchname
git branch --delete branchname
git branch -D branchname
git push origin branchname
git diff
git stash
git stash pop
git stash clear
git stash drop
git pull
git pull origin main
git log
git checkout <commithash>
git revert <commithash>
git rm <filename>
git rm -r <foldername>
git config --global user.name
git config --gloabl user.email
git config --global user.name name
git config --gloabl user.email email
git fetch
git status
