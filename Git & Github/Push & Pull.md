### Create a new repository on the command line

echo "# form.html" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/jamiealter25/git-practice-afrid.git
git push -u origin main

### Push an existing repository from the command line

git remote add origin https://github.com/jamiealter25/git-practice-afrid.git
git branch -M main
git push -u origin main