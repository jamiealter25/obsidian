
#### 1. Basic Navigation & File Operations (PowerShell)

- **Change Directory (enter folder):** `cd <foldername>`
- **Go back to parent folder:** `cd ..`
- **Create a new folder:** `mkdir <foldername>`
- **Create a new file:** `New-Item -ItemType File <filename.extension>`
    

#### 2. First-Time Setup (Run Once per Machine)

- **Set global username:** `git config --global user.name "Your Name"`
- **Set global email:** `git config --global user.email "your.email@example.com"`

#### 3. Local Repository Setup & Commits

- **Initialize Git repo:** `git init` _(short for initialize)_
- **Stage a specific file:** `git add <filename>`
- **Stage all files:** `git add .`
- **Commit staged files:** `git commit -m "Your descriptive commit message"`
- **Rename default branch to main:** `git branch -M main` _(capital `-M` forces the rename)_

#### 4. Connecting & Managing Remote Repositories

- **Connect to remote repo:** `git remote add origin <https://Link.git>`
- **Check current remote URLs:** `git remote -v`
- **Update wrong remote URL:** `git remote set-url origin [https://NewLink.git](https://NewLink.git)`
- **Remove remote connection:** `git remote remove origin`
    

#### 5. Pushing Code to Remote

- **First push (links local main to remote origin main):** `git push -u origin main`
    
- **All subsequent pushes:** `git push`


### Create a local repository & push
- open `powershel`
- go inside a file --> `cd <filename>`
- go back from a file --> `cd ..`
- `cd` means `Change Directory`
- create a folder --> `mkdir <filename>`
- create a file --> `ni <filename.extension>`
- make a git folder --> `git init`
- `init` is the short form of the `initialize`
- ready file to commit (for a specific file) --> `git add <filename>`
- ready file to commit (for all files use a dot at the end) --> `git add .`
- assign commit message --> `git commit -m "commit message"`
- connect account username first time --> `git config --global user.name "username"`
- connect account email first time --> `git config --global user.email "sample@gmail.com"`
- force rename local branch if named `master` --> `git branch -M main`
- `-m` is to assign a name, `-M` is to force assign a name.
- `add` local repo to remote repo --> `git remote add origin <https://Link.git>`
- first push to remote repo --> `git push -u origin main`
- regular code to push --> `git push`

### Extra
- if link was wrong then change it --> `git remote set-url origin <https://NewLink.git>`
- remove origin link connection --> `git remote remove origin`
- display the current URLs attached to origin --> `git remote -v`