These are first time setup
step 0: make a new repository on github

step 1: make sure that u have initilized git for the folder where u are working by running following command

git init

run above command only one time for that folder.

step 2: check for changes by following command

git status


step 3: add that file to git by following command

git add .

in above command replace the FileNAME with actual file name

step 4:
 commit the file to git database by this command

git commit -m "your message whatever you want to add inside these double brekets"

step 4:
save those changes by this command
 git push -u origin master
step 5: sometime you dont want to push some files to git
so what you do is you create a new file by this name
.gitignore
in this file you enter the name of file or folder which you dont want to push to github.
for example if you see inside cpp folder there is .gitignore file
in tthat file we have only writtern 1 line which is
*.exe
what this above line does is it tells the git to ignore all files(* mean all) with .exe extension should be ignored