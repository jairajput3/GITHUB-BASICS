# GITHUB-BASICS

if you want to change something in readme file just know basics of html

git --version
ls
clear
pwd

git config --global user.name "my name"
git config --  global user.email "@email.com"
git config --list

-------------- CLONE AND STATUS

CLONE -- cloning a repository on our local machine 
git clone https.....
git clone <-some link ->

status - displays the state of the code

cmd -->git status

### REMOTE --> MEANS file in github
### local --> file in laptop or pc

### cd --> change directory cmd -- cd folder_name
## git status -->
## after modification add commit
## 4 types of status
UNTRACKED ---> new file that git does not yet track
MODIFIED --> changed
STAGED --> file is ready to be commited
UNMODIFIED --> unchanged

### ADD and COMMIT

ADD --> adds new or changed file in your working directory to the git staging area
git add file name
COMMIT -->IT IS THE RECORD OF CHANGE
git commit -m"some message"
if u forget to close it :1q!
..
..
(git add .) for lots of file

### PUSH --> upload local repo content to remote repo
git push origin main

---------