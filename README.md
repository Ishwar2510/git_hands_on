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