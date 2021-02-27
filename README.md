# git_cheatsheet
Cheat-sheet for git commands 🔃


Since I usually face interesting challenges working with git, I decided to setup this repository to share everything interesting in git world 🌎

Free to use for anyone in anywhere 😃

## Basic commands 

1.`git init` : Initializing git in a folder or file<br />
2.`git status` : Showing the status of git files (whether they are unstaged or staged)<br />
3.`git log`: List all commits<br />
4.`git add <NAME OF FILES>` : Staging files<br />
  -`git add “page*”` : All files starting with *page* keyword<br />
  -`git add -A` : All changed files<br />
 
5-`git commit -m <MESSAGE>` : Making commitment<br />
6- `git diff HEAD` : Comparing HEAD to untagged and staged changes(doesn’t matter)<br />
7- `git diff —staged` : Comparing staged files to HEAD<br />
8 - `git reset <file>`  : unstaging a file<br />
9-  `git checkout — <file>` : changing file to last committed one (HEAD)<br />
	*Note* : if you have staged a file and want to discard the changes:<br />
		- onstage it<br />
		- check it out<br />
