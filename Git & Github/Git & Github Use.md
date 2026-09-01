
**Install git**
### Create a local repository
- open `powershel`
- go inside a file --> `cd <filename>`
- go back from a file --> `cd ..`
- `cd` means `Change Directory`
- create a folder --> `mkdir <filename>`
- create a file --> `New-Type -ItemType File <filename.extension>`
- make a git folder --> `git init`
- `init` is the short form of the `initialize`
- ready file to commit (for a specific file) --> `git add <filename>`
- ready file to commit (for all files use a dot at the end) --> `git add .`
- assign commit message --> `git commit -m "commit message"`
- connect account username first time --> `git config --global user.name "username"`
- connect account email first time --> `git config --global user.email "sample@gmail.com"`
- force rename local branch if named `master` --> `git branch -M main`
- `-m` is to assign a name, `-M` is to force assign a name.
- `add` local repo to remote repo --> `git remote add origin <https://link.git>`
- first push to remote repo --> `git push -u origin main`
- regular code to push --> `git push`
- 
### Create a new repository on the command line





### Push an existing repository from the command line

git remote add origin https://github.com/jamiealter25/git-practice-afrid.git
git branch -M main
git push -u origin main