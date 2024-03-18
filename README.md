Below is a rewritten version suitable for a README file, structured to enhance readability and organization:

---

# GitHub Commands Guide

This guide provides a concise overview of common GitHub commands, organized by functionality. Whether you're getting started with a new project, managing your files, branching and merging, sharing updates, or inspecting your repository, this reference can help streamline your workflow.

## Getting and Creating Projects

- **Initialize a Local Repository:**  
  `git init`  
  Initializes a new local Git repository.

- **Clone a Remote Repository:**  
  `git clone ssh://git@github.com/[username]/[repository-name].git`  
  Creates a local copy of a remote repository.

## Basic Snapshotting

- **Check Status:**  
  `git status`  
  Displays the status of your working directory and staging area.

- **Add Files to Staging Area:**  
  `git add [file-name.txt]`  
  Adds a specific file to the staging area.  
  `git add -A`  
  Adds all new and changed files to the staging area.

- **Commit Changes:**  
  `git commit -m "[commit message]"`  
  Records changes to the repository with a descriptive message.

- **Remove Files or Folders:**  
  `git rm -r [file-name.txt]`  
  Removes a file (or folder) from your working directory and stages the deletion.

## Branching and Merging

- **List Branches:**  
  `git branch`  
  Lists all local branches. The current branch is marked with an asterisk.  
  `git branch -a`  
  Lists all branches, local and remote.

- **Create and Manage Branches:**  
  `git branch [branch-name]`  
  Creates a new branch.  
  `git branch -d [branch-name]`  
  Deletes a local branch.  
  `git push origin --delete [branch-name]`  
  Deletes a remote branch.

- **Branch Switching and Creation:**  
  `git checkout -b [branch-name]`  
  Creates a new branch and switches to it.  
  `git checkout [branch-name]`  
  Switches to a specific branch.  
  `git checkout -`  
  Switches to the last checked out branch.  
  `git checkout -- [file-name.txt]`  
  Discards changes in your working directory to a file.

- **Merging:**  
  `git merge [branch-name]`  
  Merges the specified branch into the current branch.  
  `git merge [source-branch] [target-branch]`  
  Merges one branch into another.

- **Stashing:**  
  `git stash`  
  Stashes changes in your working directory.  
  `git stash clear`  
  Removes all stashed entries.

## Sharing and Updating Projects

- **Pushing Changes:**  
  `git push origin [branch-name]`  
  Pushes a branch to your remote repository.  
  `git push -u origin [branch-name]`  
  Pushes changes to the remote repository and sets the upstream for future pushes.  
  `git push`  
  Pushes changes to the remote repository for the current branch.

- **Updating Local Repository:**  
  `git pull`  
  Updates your local repository to the newest commit.  
  `git pull origin [branch-name]`  
  Pulls changes from a remote repository.

- **Manage Remote Repository:**  
  `git remote add origin ssh://git@github.com/[username]/[repository-name].git`  
  Adds a new remote repository.  
  `git remote set-url origin ssh://git@github.com/[username]/[repository-name].git`  
  Sets a repository's origin branch to SSH.

## Inspection and Comparison

- **View Changes:**  
  `git log`  
  Views commit history.  
  `git log --summary`  
  Views detailed commit history.  
  `git log --oneline`  
  Views a brief summary of commit history.

- **Preview Changes Before Merging:**  
  `git diff [source-branch] [target-branch]`  
  Previews changes between branches before merging.

---

Feel free to adjust any parts of this guide to fit your project's specific needs or preferences.
