# TestGitHUB
GitHub Tutorial
===============

TestGitHUB is a  repository for showing the bare minimum of github and how to manouver, functions, etc.
=======================================================================================================

Things Learnt : 

Create new repository on GitHub Account 

Installed git on my machine

git config --global user.name "AbhishekPandey12" : Specify Username

git config --global user.email "abhisonu3629@gmail.com" : Specify Email

Move to the folder where you want to clone(checkout) the github repository that you created on the first place

git clone and paste that aove url : copy the URL and type

If want to see what all files are there you can do "ls"

vm README.md : For reading a particular file in Bash Window go to the directory and then write the command written beforehand.

:x is to save what we have written so far in vm

git status : Just tells what's modified,what's not the changes it talks about.

git add README.md : To add the changes. Add the Changes to the staging area, we arenot actually pushing to the Repo, Staging area means place                           somewhere between Local and Repo

git commit -m "Commit_Statement": Its also not actually pushing to the repo, Documenting the change and finallizing the staging area to be pushed                                     to Repo.

git log : To know the history.

git status(always good)

git remote add origin https://github.com/Abhishekpandey12/TestGitHUB.git : If we have not cloned, add remote origin to which we are pushing to(Not                                                                            Required).

git push -u origin master(-u : Save, origin : From my Local, master : To Branch(now its main Branch only so master))

Type your Uname/pwd

And then the changes are reflected in the Repo

touch testfile.txt : To create a new file 