Explanation of version control
Version control, also known as source control or revision control, is a system that helps track changes to files over time.
It is commonly used in software development to manage the evolution of source code, but it can also be applied to various types of files and projects. 
The primary goals of version control are to facilitate collaboration among multiple contributors, keep a history of changes, and provide the ability to revert to previous 
states of the project.

Difference between git and github
Git:

Definition: Git is a distributed version control system designed to manage and track changes in source code during software development.
Functionality: It allows multiple developers to work on a project simultaneously by keeping a complete history of changes. Developers can create branches, make changes, commit those changes, and merge them back into the main codebase.
Operates Locally: Git operates on a local machine, meaning that users can work on their projects without the need for a constant internet connection. It enables offline work and provides fast performance.

GitHub:

Definition: GitHub is a web-based platform that provides hosting for Git repositories along with additional collaboration and project management features.
Hosting and Collaboration: GitHub allows developers to host their Git repositories in the cloud. It provides a centralized location for collaboration, code review, issue tracking, and project management.
Web Interface: GitHub offers a web-based interface that makes it easy to browse repositories, view commit histories, manage issues, and collaborate with other developers. It also provides pull requests for code review and integration.

Three other git hub alternatives 
gitlab
bitbucket
sourceForge

git rebase is a Git command used to combine and rearrange commits in a more organized way. It allows you to modify the commit history of a branch. Instead of merging changes as a new commit, it integrates the changes directly into the existing commit history.
and the command is git rebase <base_branch>.

git cherry-pick is a Git command that allows you to apply a specific commit from one branch to another. It's useful when you want to pick and choose individual commits and apply them elsewhere, independently of the commit history.Usually, when you merge branches, you bring all the changes from one branch into another, creating a merge commit.

With git cherry-pick, you can select specific commits from one branch and apply them directly to another branch without merging the entire branch

