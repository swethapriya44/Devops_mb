# Devops_mb
git init
echo "# DevOps" > README.md
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/username/repo.git
git push -u origin main
git checkout -b MITS
echo "update" >> README.md
git add .
git commit -m "MITS update"
git checkout main
git merge MITS
git push
git log
git clone https://github.com/username/repo.git
