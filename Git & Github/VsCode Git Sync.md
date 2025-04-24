Prerequisites
- Install VsCode
- Install Git
- Create GitHub Account

#Steps
1) Create a folder in local machine
2) Paste your files inside the folder (don't leave folder empty)
3) Create a repo in GitHub
4) 




- Install Git
	- check 'Additional Icons' while install
	- select 'Override the default branch' while install
	- open git bash and check `git --version`
	- assign global username `git config --global user.name "My Name"`
	- assign global email `git config --global user.email "whatever@mail.com"`
	- check assigned configuration `git config --list`



- Open VsCode terminal
	- Check `git --version`
	- If doesn't work then try [[⚠️ Issues & Solutions]]
	- Copy HTTPS link from GitHub Repo
	- Inside vscode terminal type this `git clone (link)` (to make copy of remote repo copy to local machiene)
	- get inside repo directory `cd (directory)`
	- check all files inside repo dir `ls`
	- check all files with hidden files `ls -a`
	- check if file has any differences `git diff (filename)`
	- to quick refresh if file is not changing status `git update-index --really-refresh
	- check if anything changed `git status`
	- add all file for commit `git add .`
	- commit file `git commit -m "commit note"`
	- push (upload) file `git push origin (directory)`