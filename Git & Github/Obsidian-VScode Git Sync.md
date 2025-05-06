## Prerequisites
- Install Obsidian/VScode
- Create GitHub Account
- Install Git
	- select 'Additional Icons' while install
	- select 'Override the default branch' while install
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
4) Go to the local machine folder --> `cd (folder path)`
5) Paste this in Powershell/Bash --> `git init`
6) Copy HTTPS link from remote repo
7) Connect local to remote repo (use the HTTPS) --> `git remote add origin (HTTPS link)`
8) check the .git hidden file in Bash --> `ls -a`
9) Config this folder as safe --> `git config --global --add safe.directory .`
10) Add files to repo --> `git add .`
11) Check status of local --> `git status`
12) Commit initial files to repo --> `git commit -m "Initial commit"`
13) Push files from local to repo --> `git push -u origin main`

## Pull from Remote repo
1) Create a folder in local machine
2) Open PowerShell/Bash as admin
3) Go to the local machine folder --> `cd (folder path)`
4) Copy HTTPS link from remote repo
5) Paste this in Powershell/Bash --> `git clone (HTTPS link)`
6) check the .git hidden file in Bash --> `ls -a`
7) Config this folder as safe --> `git config --global --add safe.directory .`
8) Add files to repo --> `git add .`
9) Check status of local --> `git status`
10) Commit initial files to repo --> `git commit -m "Initial commit"`
11) Push files from local to repo --> `git push -u origin main`

## Now open folder in Obsidian/VScode and push after use.

