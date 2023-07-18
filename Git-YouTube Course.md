# Git YouTube Course

## DevOps Life Cycle

1-Continuous Development
2-Continuous testing
3-Continuous integration
4-Continuous deployment
5-Continuous monitoring


### Create UserAccount for use repository

```bash
git config --global user.name /a.khosrotaj/
```
### Show user list

	$Git config --global

### Set personal Mail

	$Git config --global user.email "akhosrotaj@eridanus.ir"

-----------------------------------------------------------
### Show location

	$pwd

### show file
	
	$ls
	$ll
	$ls -a

-----------------------------------------------------------
### Git repository

command to initialize a new Git repository. This command creates a hidden .git folder that tracks changes in your project

	$Git init

----------------------------------------------------------
### Tracking File Step by Step

	$Git add .
	$Git Status
	$Git commit -m " .......commente....... "
	$Git log
	$Git diff

----------------------------------------------------------
## Remote repository

### Copy files Remote > Local

### Clone
	$Git clone -b main .......Remote Address.......

### Pull&Push
***Remote > Local = $Git Pull***
***Local > Remote = $Git Push***
---------------------------------------------------------
## Branch 

### show Branch list
	$git branch

### Create New
	$git branch .....branch name.....

### Switch Between two branch
	$git switch .....name.....

### transfer local Branch to remote Repository
	$git push origin .....branch name.....
--------------------------------------------------------
### Create file on Git Bash

	$touch ...fie name... .md
	$echo ".....Text....." >> ...file name... .md
--------------------------------------------------------
## Merge

### merge 2 branch on Remote Repository

1- Login to GitHub
2- click to *Pull Request*
--------------------------------------------------------
### Create branch and login
	$git checkout -b ....branch name....
--------------------------------------------------------
### merge 2 branch on Local Repository

	$git checkout ....main branch....
	$git merge ....sub branch....

### checks and show
	$ls -a

### push on Remote Repository
	$git add .
	$git commit
	$git push
--------------------------------------------------------
## Reset - Revert

### Reset
All <commit> have been removed until the desired <commit>

### Revert
Create new <commit> and revert to desired <commit> (undo Additional steps)

*** If changes have been made on a Local Repository >>> <Reset>
*** If changes have been made on a Remote Repository >>> <Revert>

### Show Logs & spacial commet ID
	$git log --oneline

	$git Reset --soft ....Special commet ID....

***By using the --soft command, you can perform a reset without deleting the files***
***By using the --hard command, you can perform a reset deleting the files***
---------------------------------------------------------

## Stash

Commit is temporarily converted to WIP(working in progres) mode

	$git stash

	$git stash list

Restore again stash commet

	$git stash apply
	$git status		

***after push commit we need clear stash list***

	$git stash drop

### Stash Untrack File

	$git stash -a

### stash apply+drop for both (track & untrack file)

	$git stah pop stash{..Stash ID..}

***we can comment for stash commete***

	$git stash save "....commente..."	
	$git stash save -a "....commente..."
