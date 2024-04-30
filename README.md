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




