# Git YouTube Course

## DevOps Life Cycle

1-Continuous Development
2-Continuous testing
3-Continuous integration
4-Continuous deployment
5-Continuous monitoring


## Create UserAccount for use repository

$Git config --global user.name /a.khosrotaj/

## Show user list

$Git config --global

## Set personal Mail

$Git config --global user.email "akhosrotaj@eridanus.ir"

-----------------------------------------------------------
## Show location

$pwd

## show file

$ls
$ll
$ls -a

-----------------------------------------------------------
## Git repository

command to initialize a new Git repository. This command creates a hidden .git folder that tracks changes in your project

$Git init

----------------------------------------------------------
## Tracking File Step by Step

$Git add .
$Git Status
$Git commit -m " .......commente....... "
$Git log
$Git diff

----------------------------------------------------------
### Remote repository

##Copy files Remote > Local

#Clone
$Git clone -b main .......Remote Address.......

#Pull&Push
**Remote > Local = $Git Pull
**Local > Remote = $Git Push
