
**Install git**
### Create a local repository
- open 'powershell'
- go inside a file --> `cd <filename>`
- go back from a file --> `cd ..`
- create a folder --> `mkdir <filename>`
- create a file --> `New-Type -ItemType File <filename.extension>`
- make a git folder --> `git init`
- `init` is the short form of the `initialize`
- ready file to commit (for a specific file) --> `git add <filename>`
- ready file to commit (for all files use a dot at the end) --> `git add .`
- assign commit message --> `git commit -m "commit message"`
- force rename local branch if named `master` --> `git branch -M main`
- `-m` is to assign a name, `-M` is to force assign a name.
### Create a new repository on the command line

git branch -M main
git remote add origin https://github.com/jamiealter25/git-practice-afrid.git
git push -u origin main

### Push an existing repository from the command line

git remote add origin https://github.com/jamiealter25/git-practice-afrid.git
git branch -M main
git push -u origin main