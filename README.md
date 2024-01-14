## My-learnable-task-2

<p> Version control is a system that manage changes to a project's source code or file over time. It allows multiple contribution to work on the file concurrently, track modifications, and facilitates collaboration by providing a history of changes.</p>

# Git is a distributed version control system that allow you to track changes to your codebase, collaborate with others and manage different version of your project locally.

# Github on the other hand is a web-based platform that provide hosting for software development using Git it add a layer a layer of collaboration features on the top of Git, allowing multiple developers to work on a project, manage issue and contribute to repositories hosted on Github platform.

# In summary, Git is the version control system, while Github is a web-based platform that utilizes Git for collaborative software development and provides additional tools and feature

# Three other Github alternatives includes

# BitBucket

# GitLab

# SourceForge

# git fetch and git pull are both git command used to update your local repository with changes from remote repository but they differs in their approach

# git fetch retrieves changes from the remote repository but does not automatically merge them into your working branch. It is useful for reviewing changes before deciding to merge. Fetching does not modify your working directory and you need to explicitly merge the fetched changes if desired.

# While git pull on the other hand fetches changes from the remote repository and automatically merge them into your working branch. It provide a more streamlined way to fetch and merge changes in one command.

# git rebase is a Git command used to modify the commit history of a branch. it rewrite the commit history by moving, combining or eliminating commit. Unlike git merge, which create a new commit to merge changes, git rebase integrates changes by placing the entire sequence of commits into a new base commit

# The command for the rebase is

# git checkout develop_branch to migrate to develop_branch

# git rebase main

# git cherry-pick is a git command that allow you to apply a specific commit from one branch to another. It takes a change introduced by a commit and place a new commit with those changes onto the branch you are currently on. This command will apply the changes from the specified commit to your current branch. if there are no conflicts, Git will create a new commit with the changes. if conflicts arise, you will need to resolve them before completing the cherry-pick. git cherry-pick is useful when you want to selectively bring in changes from one branch to another without merging the entire branch.

# The command for the cherry-pick is

# git cherry-pick <commit-hash>
