# What is Gitflow Workflow ?
## Gitflow Workflow is a Git workflow design that was first published and made popular by Vincent Driessen at nvie. The Gitflow Workflow defines a strict branching model designed around the project release. This provides a robust framework for managing larger projects.
# The overall flow of Gitflow is:
1. A develop branch is created from master
2. A release branch is created from develop
3. Feature branches are created from develop
4. When a feature is complete it is merged into the develop branch
<<<<<<< HEAD
5. When the release branch is done it is merged into developand master
=======
5. When the release branch is done it is merged into develop and master
>>>>>>> 25bc5f6ccab2c340e65457aaeaf5746adbb0cd2a
6. If an issue in master is detected a hotfix branch is created from master
6. Once the hotfix is complete it is merged to both develop and master
# Repository
## A digital directory or storage space where you can access your project, its files, and all the versions of its files that Git saves.
<<<<<<< HEAD
# Clone 
=======
# Clone
>>>>>>> 25bc5f6ccab2c340e65457aaeaf5746adbb0cd2a
## A clone is simply a copy of a repository.
# Fork
## A fork is a copy of a project folder (repository) into your login or onto your desktop if you use Github on your Desktop.
# Branch
<<<<<<< HEAD
## A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master. 
# Commit
## A commit, or "revision", is an individual change to a file (or set of files).
# Merge
## Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. 
# Checkout
## The action of updating all or part of the working tree with a tree object or blob from the object database, and updating the index and HEAD if the whole working tree has been pointed at a new branch. 
=======
## A branch in Git is simply a lightweight movable pointer to one of these commits. The default branch name in Git is master.
# Commit
## A commit, or "revision", is an individual change to a file (or set of files).
# Merge
## Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another.
# Checkout
## The action of updating all or part of the working tree with a tree object or blob from the object database, and updating the index and HEAD if the whole working tree has been pointed at a new branch.
>>>>>>> 25bc5f6ccab2c340e65457aaeaf5746adbb0cd2a
# Push
## Pushing refers to sending your committed changes to a remote repository, such as a repository hosted on GitHub. For instance, if you change something locally, you'd want to then push those changes so that others may access them.
# Pull
## Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date.
# Remote Add / Remove / Show
## This is the version of something that is hosted on a server, most likely GitHub. It can be connected to local clones so that changes can be synced.
# Status
<<<<<<< HEAD
## A status is a type of status check on GitHub.Status checks are external processes, such as continuous integration builds, which run for each commit you make in a repository. 
=======
## A status is a type of status check on GitHub.Status checks are external processes, such as continuous integration builds, which run for each commit you make in a repository.
>>>>>>> 25bc5f6ccab2c340e65457aaeaf5746adbb0cd2a
# Master branch
## The default development branch. Whenever you create a Git repository, a branch named "master" is created, and becomes the active branch. In most cases, this contains the local development, though that is purely by convention and is not required.
