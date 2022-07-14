# Projects
$ git clone <url>
# your team project 

$ cd <folder-name>
# past inside your code or files(which you are working and Delete others code or unnecessry files)

#  to check file inside your folder(your project data list)
$ ls

# to Creat Branch
$git checkout -b branch-name

#to go your  branch(make sure your project with new branch)
$git checkout branch-name

#to check branch avilable  or not( your Current Branch or list out  all)
$git branch -a  

#add file in remote
$git add .

#Commit with msg
$git commit -m "Branch-msg" 


# To push in Your Code
$ git push --set-upstream origin branch-name

>>> !!! Done now Check On Gitlab your Code !!!!!

################# After Some Changes ....
$git status #(Check Status)(red-local/Green-remote)

#to go your  branch(make sure your project)
$git checkout branch-name

#add file in remote
$git add .

#Commit with msg
$git commit -m "Branch-new-msg" 


# To push in Your Code
#git push origin

>>> !!! Done now Check On Gitlab your Code !!!!!

######################!! if Required !!####################################
Git global setup
git config --global user.name "Your_Name"
git config --global user.email "your@email.com"



###########
Push an existing folder
cd existing_folder

git init --initial-branch=main
git remote add origin <url>

git add .
git commit -m "Initial commit"
git push -u origin main



