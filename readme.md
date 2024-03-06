# Git Commands and Operations


## Basic Git Commands

- **`git init`**: Initialize a new Git repository in your project directory.
- **`git clone <repository-url>`**: Clone an existing repository to your local machine.
- **`git status`**: Check the status of your working directory and staging area.
- **`git add <file>`**: Add a file or changes to the staging area.
- **`git commit -m "<message>"`**: Commit your staged changes with a descriptive message.
- **`git push`**: Push your local commits to the remote repository.
- **`git pull`**: Fetch changes from the remote repository and merge them into your local branch.
- **`git branch`**: List all branches in your repository. Use `-a` to see remote branches as well.
- **`git checkout <branch-name>`**: Switch to a different branch.
- **`git merge <branch-name>`**: Merge the specified branch into your current branch.

## Branching and Merging

- **Creating a new branch**: `git branch <new-branch-name>`
- **Switching to a branch**: `git checkout <branch-name>`
- **Merging a branch into the current branch**: `git merge <branch-name>`
- **Deleting a local branch**: `git branch -d <branch-name>`

## Stashing Changes

- **Stash changes**: `git stash`
- **List stashed changes**: `git stash list`
- **Apply stashed changes**: `git stash apply`
- **Drop a stash**: `git stash drop`

## Viewing History

- **View commit history**: `git log`
- **View specific file changes**: `git log -p <file>`
- **View changes since a specific commit**: `git log <commit-hash>..HEAD`

## Undoing Changes

- **Revert a commit**: `git revert <commit-hash>`
- **Reset to a specific commit**: `git reset --hard <commit-hash>`
- **Unstage a file**: `git reset HEAD <file>`

## Collaboration

- **Fetching changes from a remote repository**: `git fetch <remote-name>`
- **Pushing changes to a remote branch**: `git push <remote-name> <branch-name>`
- **Pulling changes from a remote branch**: `git pull <remote-name> <branch-name>`

## Advanced Git Operations

- **Rebasing**: `git rebase <branch-name>`
- **Cherry-picking**: `git cherry-pick <commit-hash>`
- **Interactive rebase**: `git rebase -i <commit-hash>`

