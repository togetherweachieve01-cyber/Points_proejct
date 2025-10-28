# Points_proejctgit clone https://github.com/<you>/<repo>.git
cd <repo>
echo "# <repo>" > README.md
git init
git branch -M main
git add README.md
git commit -m "chore: init repo"
git remote add origin https://github.com/<you>/<repo>.git
git push -u origin main
