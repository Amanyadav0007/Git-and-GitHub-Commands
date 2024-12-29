# Git-and-GitHub-Commands

This table provides a comprehensive list of commonly used Git and GitHub commands, categorized for easy reference.

| **Category**              | **Command**                           | **Description**                                                                 |
|---------------------------|---------------------------------------|---------------------------------------------------------------------------------|
| **Setup and Configuration** | `git --version`                     | Check installed Git version.                                                   |
|                           | `git config --global user.name "Your Name"` | Set your Git username.                                                         |
|                           | `git config --global user.email "your.email@example.com"` | Set your Git email address.                                                    |
|                           | `git config --list`                  | View all Git configurations.                                                   |
|                           | `git help <command>`                 | Get help for a specific Git command.                                           |
| **Starting a Repository** | `git init`                           | Initialize a new Git repository.                                               |
|                           | `git clone <repo-URL>`               | Clone a remote repository to your local machine.                               |
| **Staging and Committing** | `git add <file>`                    | Stage a specific file.                                                         |
|                           | `git add .`                          | Stage all changes in the repository.                                           |
|                           | `git status`                         | Show the status of changes (staged, unstaged, untracked).                      |
|                           | `git commit -m "message"`            | Commit staged changes with a descriptive message.                              |
|                           | `git commit --amend`                 | Edit the last commit message.                                                  |
| **Branching**             | `git branch`                         | List all branches in the repository.                                           |
|                           | `git branch <branch-name>`           | Create a new branch.                                                           |
|                           | `git checkout <branch-name>`         | Switch to a specific branch.                                                   |
|                           | `git checkout -b <branch-name>`      | Create and switch to a new branch.                                             |
|                           | `git branch -d <branch-name>`        | Delete a branch locally.                                                       |
| **Merging**               | `git merge <branch-name>`            | Merge a branch into the current branch.                                        |
|                           | `git merge --abort`                  | Abort a merge in case of conflicts.                                            |
| **Viewing Changes**       | `git log`                            | View the commit history.                                                       |
|                           | `git log --oneline`                  | View the commit history in one-line format.                                    |
|                           | `git diff`                           | Show unstaged changes.                                                         |
|                           | `git diff <branch1> <branch2>`       | Compare two branches.                                                          |
| **Undoing Changes**       | `git reset <file>`                   | Unstage a file.                                                                |
|                           | `git reset --hard`                   | Reset to the last commit, discarding all changes.                              |
|                           | `git checkout -- <file>`             | Discard changes in a file.                                                     |
| **Working with Remotes**  | `git remote -v`                      | List remote repositories.                                                      |
|                           | `git remote add origin <repo-URL>`   | Link a local repository to a remote repository.                                |
|                           | `git push -u origin main`            | Push the main branch to the remote repository and set upstream.                |
|                           | `git pull origin main`               | Fetch and merge changes from the remote repository's main branch.              |
|                           | `git fetch`                          | Download changes from a remote repository without merging.                     |
| **Tagging**               | `git tag`                            | List all tags in the repository.                                               |
|                           | `git tag <tag-name>`                 | Create a new tag.                                                              |
|                           | `git push origin <tag-name>`         | Push a specific tag to the remote repository.                                  |
| **Collaborative Work**    | `git stash`                          | Save uncommitted changes for later.                                            |
|                           | `git stash pop`                      | Apply the latest stashed changes and remove them from the stash list.          |
|                           | `git stash list`                     | View the list of stashes.                                                      |
|                           | `git rebase <branch-name>`           | Reapply commits from another branch on top of the current branch.              |
| **Cleanup**               | `git clean -f`                       | Remove untracked files.                                                        |
| **Additional Commands**   | `git show <commit-hash>`             | Show details of a specific commit.                                             |
|                           | `git blame <file>`                   | View who last edited each line of a file.                                      |
|                           | `git cherry-pick <commit-hash>`      | Apply a specific commit from one branch to another.                            |

## Notes
- Replace placeholders like `<repo-URL>`, `<file>`, `<branch-name>`, `<tag-name>`, and `<commit-hash>` with your specific values.
- Use the `--help` option with any Git command to get detailed information about its usage, e.g., `git commit --help`.

---

Feel free to use this table as a quick reference for your Git and GitHub commands!
Follow @curious_coder_aman on Instagram for more coding updates.
