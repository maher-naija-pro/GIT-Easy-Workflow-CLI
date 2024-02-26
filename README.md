# GIT-Easy-Workflow-CLI

This project target 

**1- To make working with git easy for any one without undestending git concepts and workflow** \
**2- Make git workflow faster with less steps**


# Dependency
Git cli 


# Features:


### CLI auto complete

Press tab tab to get suggestions

### Manage repo
repo   empty     init  : git init / git store credential / git set login pass / create dev qa  prod branches \
repo   donwload        : git clone repo  / git store credential / git set login pass \



### Manage bugfixs
repo create bugfix        : create bug branch / git chekcout branch\

repo save   bugfix local  : git add / git commit \
repo save   bugfix server : git add / git commit / git push \

repo sync   bugfix prod   : git merge master to bug branch \

repo send   bugfix dev    : git merge dev to bugfix / git merge bug fix to dev  \
repo send   bugfix qa     : git merge qa to bugfix / git merge bug fix to qa \
repo send   bugfix prod   :  git merge prod to bugfix / git merge bug fix to prod \

repo undo   bugfix local  : git reset  \
repo undo   bugfix server : git revert / git push \

### Manage features

repo save   feature  local  : git add / git commit \
repo save   feature server : git add / git commit / git push \

repo sync   feature  prod   : git merge master to bug branch \

repo send   feature dev    : git merge dev to bugfix / git merge bug fix to dev \
repo send   feature qa     : git merge qa to bugfix / git merge bug fix to qa \
repo send   feature prod   :  git merge prod to bugfix / git merge bug fix to prod \

repo undo   feature local  : git reset \
repo undo   feature server : git revert / git push \

### Manage platforms

repo undo prod : git revert prod / git push  \
repo undo qa   : git revert qa /git push \
repo undo dev  : git revert dev /git push  \
