git checkout -b progress

git remote add jwasham https://github.com/jwasham/coding-interview-university

git fetch --all
git add .

git commit -m "Marked x"

git rebase jwasham/master

git push --force
[]check this out
