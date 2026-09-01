
#### 1. Basic Navigation & File Operations (PowerShell)

- **Change Directory (enter folder):** `cd <foldername>`
- **Go back to parent folder:** `cd ..`
- **Create a new folder:** `mkdir <foldername>`
- **Create a new file:** `ni <filename.extension>`

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
- **Update wrong remote URL:** `git remote set-url origin <https://NewLink.git>`
- **Remove remote connection:** `git remote remove origin`

#### 5. Pushing Code to Remote

- **First push (links local main to remote origin main):** `git push -u origin main`
- **All subsequent pushes:** `git push`

#### 6. Branching & Merging Operations (Task 5, 6 & 9)

- **Create and switch to a new branch:** `git checkout -b <branch-name>` 
- **Switch back to an existing branch:** `git checkout <branch-name>`
- **Merge a branch into your current branch:** `git merge <branch-name>`
- **Delete a branch after merging:** `git branch -d <branch-name>`
