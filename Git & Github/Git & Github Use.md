
#### 1. Basic Navigation & File Operations (PowerShell)

- **Change Directory (enter folder):** `cd <foldername>`
- **Go back to parent folder:** `cd ..`
- **Create a new folder:** `mkdir <foldername>`
- **Create a new file:** `ni <filename.extension>`

#### 2. Configure and Sign into an account (Run Once per Machine)

- **Set global username:** `git config --global user.name "Your Name"`
- **Set global email:** `git config --global user.email "your.email@example.com"`
- **Check the signed in account's credentials:** `git config --get-regexp user`
- **Signs out of the Account:** `git credential-manager github logout <username>`

#### 3. Local Repository Setup & Commits

- **Initialize Git repo:** `git init` _(short for initialize)_
- **Stage a specific file:** `git add <filename>`
- **Stage all files:** `git add .`
- **Commit staged files:** `git commit -m "Your descriptive commit message"`
- **Rename default branch from master to main:** `git branch -M main` _(capital `-M` forces the rename, always change 'master' to 'main' cause 'master' name is no longer used)_

#### 3. Repository Status
- **Check the current status of branch** `git status`

    **4 types of git status:**
    - **untracked:** New file sthat git doesn't track yet
    - **modified:** Changed file
    - **staged:** File is ready to be commited
    - **unmodified:** Unchanged file

#### 4. Connecting & Managing Remote Repositories

- **Connect to remote repo:** `git remote add origin <https://Link.git>`
- **Check current remote URLs:** `git remote -v`
- **Update wrong remote URL:** `git remote set-url origin <https://NewLink.git>`
- **Remove remote connection:** `git remote remove origin`

#### 5. Pushing Code to Remote

- **First push (links local main to remote origin main):** `git push -u origin main`
- **All subsequent pushes:** `git push`

#### 6. Branching & Merging Operations

- **To check branch list:** `git branch`
- **Create and switch to a new branch:** `git checkout -b <branch-name>` 
- **Rename a branch**: `git branch -M <branch-name>`
- **Switch to any existing branch:** `git checkout <branch-name>`
- **To check the differences before commit:** `git diff` _(press 'q' to quit)_
- **Merge a branch into your current branch:** `git merge <branch-name>`
- **Push a branch**: `git push origin <branch-name>`
- **Delete a branch after merging:** `git branch -d <branch-name>`
- **To pull a branch from remote:** `git pull origin <branch-name>`

#### 7. Cloning Repositories

- **Clone an existing repository from remote:** `git clone <https://NewLink.git>`


#### Merge Conflicts

#### Fork

#### PR (Pull Request)

#### Undoing Changes
- **Undo staged changes (single file):** `git reset <filename>`
- **Undo staged changes (all file):** `git reset'
- **Undo commited changes (go one commit back):** `git reset HEAD~1`
- **Undo commited changes (for many commits):** `git reset --hard <commit_hash>`