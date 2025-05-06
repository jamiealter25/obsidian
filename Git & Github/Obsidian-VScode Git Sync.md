## Prerequisites
- Install Obsidian/VScode
- Create GitHub Account
- Install Git
- check git version `git --version`
- configure git
	- git config --global username "My Name"
	- git config --global user.email "someone@email.com"
- check configure `git config --list`
- create classic token instead of password
## Push from Local repo
1) Create a folder in local machine & put files inside
2) Create a repo in GitHub
3) Open PowerShell/Bash as admin
4) Go to the local machine folder - `cd (folder path)`
5) Paste this in Powershell/Bash - `git init`
6) Copy HTTPS link from remote repo
7) Connect local to remote repo (use the HTTPS) - `git remote add origin (HTTPS link)`
8) Config this folder as safe `git config --global --add safe.directory (foler path)`
9) Add files to repo - `git add .`
10) Check status of local - `git status`
11) Commit initial files to repo - `git commit -m "Initial commit"`
12) Push files from local to repo - `git push -u origin main`


## Pull from Remote repo
1) Create a folder in local machine
2) Open PowerShell/Bash as admin
3) Go to the local machine folder - `cd (folder path)`
4) 




4) Go to obsidian and 'Open folder Vault'
5) Open the local folder you created for remote repo
6) Install 'Git' plugin in obsidian and Enable it
7) Go to 'Git' plugin settings and put `sync time` here 'Auto commit-and-sync interval (minutes)'
8) Now edit your files in local repo and wait till `sync time`
9) After `sync time` go to GitHub and reload to check if it's updating automatically

