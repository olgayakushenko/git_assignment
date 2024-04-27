# Git Assignment - olgayakushenko

a. What is an issue?

An issue in Git/GitHub is a feature used to track ideas, enhancements, tasks, or bugs associated with a repository. It's a centralized place for collaboration and discussion among contributors.

b. What is a pull request?

A pull request (PR) is a proposed change to a repository hosted on platforms like GitHub. It enables contributors to suggest changes, submit code, and collaborate on projects. Pull requests provide a way for others to review the changes before they are merged into the main codebase.

c. How do I open up a pull request?

Fork the repository if you don't have write access.
Create a new branch from the main branch.
Make your changes in the new branch.
Push the branch to your forked repository.
Go to the original repository and click on the "New pull request" button.
Select your branch and the branch you want to merge your changes into.
Provide a title and description for your pull request.
Click "Create pull request" to submit it for review.

d. Give me a step by step guide on how to add someone to your repository.

Go to your repository on GitHub.
Click on the "Settings" tab.
In the left sidebar, click on "Manage access."
Click on the "Invite a collaborator" button.
Enter the GitHub username, email, or name of the person you want to add.
Select the appropriate permission level.
Click on "Add [username]" to invite them to collaborate.

e. What is the difference between git and GitHub?

Git is a distributed version control system used for tracking changes in source code during software development. GitHub is a web-based platform that provides hosting for Git repositories, along with collaboration features like issue tracking, pull requests, and project management.

f. What does git diff do?

git diff is a Git command that shows the differences between commits, branches, or the working directory. It highlights added, modified, and deleted lines of code to provide a clear view of changes made.

g. What is the main branch?

The main branch (formerly commonly named "master" but increasingly named "main" for inclusivity) in Git/GitHub is the default branch where the latest changes and contributions are typically merged. It represents the stable version of the project.

h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

It's generally not recommended to push changes directly to the main branch, especially in collaborative environments or for larger projects. Instead, it's best practice to create a new branch for each feature or fix, make changes there, and then open a pull request for review and integration into the main branch. This allows for better code review, testing, and ensures that the main branch remains stable.