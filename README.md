
Project Repository Setup and Documentation
## Project OverView

Welcome to the Blog-App repository! This project involves to view blogs , add comments and much more. 
Whether you are a seasoned writer or just starting, this app provides a user-friendly platform for expressing your thoughts and ideas.This README file provides instructions on setting up the project, executing tasks, and handling common scenarios like branching and resolving merge conflicts.

## Table of Contents:

Initial Setup
Committing to GitHub
Branching
Merge Conflict Resolution
Project Execution

# Initial setup:
1. Clone the repository:
git clone git@github.com:BharathReddy023/Blog-App-Git.git
cd Blog-App-Git
2. Initialize Git:
git init
3. Link to github:
Create a new repository on GitHub.
Copy the remote repository URL.
Link your local repository to the GitHub repository:

git remote add origin git@github.com:BharathReddy023/Blog-App-Git.git

 # Committing to Github:
 1. first  add code to staqging area by 
  git add .(file path)
 2. commit code by
  git commit -m "commit message here"
 3. Push code to Git hub :
    git push --set-upstream origin master

# Branching:
1. Create a New Branch:
git checkout -b branch-name
2. Switch Between Branches:
 git checkout <branch_name>
3. Merge Branches:
 Switch to the branch you want to merge into
git checkout master

 Merge the feature branch into master
git merge feature-branch

# Merge Conflict Resolution:
Generate Conflict:

Intentionally modify the same file on two different branches.
Resolve Conflict:
Check the screenshots attached 
Manually edit the conflicted file.

# Mark conflicts as resolved:
git add <conflicted_file>
Continue the merge process:
git merge --continue
Verify Resolution:
git log --merge

git add <conflicted_file>
Continue the merge process:

git merge --continue
Verify Resolution:
git log --merge

## Project Execution:Install Dependencies:
npm install 
Run the Project:
npm start

Now you can see the project is running and you can view blogs by entering username and password
You can add comments for specific blogs and much more .

Feel free to reach out for any questions or clarifications. Happy coding! 🚀



