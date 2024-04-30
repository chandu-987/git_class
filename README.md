echo "# git_class" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M trunk
git remote add origin git@github.com:chandu-987/git_class.git
git push -u origin trunk

--------------------------------------------------------------
README.md file created in local and remote stages 
--------------------------------------------------------------

git there are four stages 

1. working area
2. staging area 
3. local area
4. remote area

working area :- README.md file will be created
staging area :- git add . -------REAMDME.md file add to staging (git add .)
local area :-  git commit ------ README.md ,, file (index.html)
remote area : git push ---------README.md file


---------------------------------------------------------------
git log info= commit ID's and author details are shown
---------------------------------------------------------------


Explained about VCS?
Difference between Centralised[SVN] and Distributed VCS [GITHUB]
Create GITHUB account
Download git bash
create repository in github [remote repository]
git cmds
---------
 Getting Started - First-Time Git Setup 
# ------path]/etc/gitconfig file
# add global configurations
    git config --global user.email "vignan.kandelab@gmail"
    git config --global user.name "john Doe"
# To show branch name in "git log" outputs
    git config --global log.decorate auto
    
# starting local repository
        git init   --> Create repository
        git status     # u may get untracked files and floders
        git add .      # move files to staging
        git commit -m " give some message related to the changes" --> moves files to local repo
#  Git that you want to add a new remote repository.
        git remote add origin <git repository url >
# git remote add origin 
        git push -u origin master/main            # depends on branch

