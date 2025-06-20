# Git & GitHub Functionalities Reference

## Git Basics
| Command        | Description                                           |
|----------------|-------------------------------------------------------|
| `git init`     | Initialize a new Git repository                      |
| `git clone`    | Clone a remote repository                            |
| `git config`   | Configure Git (user name, email, aliases, etc.)      |
| `git status`   | Show current working directory state                 |
| `git add`      | Stage changes                                        |
| `git commit`   | Save staged changes to history                       |
| `git log`      | View commit history                                  |

## Branching & Merging
| Command            | Description                                         |
|--------------------|-----------------------------------------------------|
| `git branch`       | Create, list, or delete branches                   |
| `git checkout`     | Switch to another branch or restore files          |
| `git switch`       | Modern alternative to checkout (for branches)      |
| `git merge`        | Merge changes from one branch into another         |
| `git rebase`       | Reapply commits on top of another base tip         |
| `git stash`        | Save uncommitted changes temporarily               |
| `git cherry-pick`  | Apply a specific commit to current branch          |

## Remote Repositories
| Command            | Description                                         |
|--------------------|-----------------------------------------------------|
| `git remote`       | Manage set of tracked repositories                 |
| `git fetch`        | Download updates from remote                      |
| `git pull`         | Fetch + merge changes from remote                 |
| `git push`         | Upload local changes to remote                    |
| `git remote add`   | Add a new remote repo                             |

## Undoing & Fixing
| Command            | Description                                         |
|--------------------|-----------------------------------------------------|
| `git reset`        | Undo changes (soft, mixed, hard resets)            |
| `git revert`       | Create a new commit that undoes previous commit    |
| `git restore`      | Restore files to previous state                    |
| `git clean`        | Remove untracked files                             |
| `git commit --amend` | Update the last commit (e.g., add forgotten file) |

## Common Git Shortcuts & Combined Commands
| Command                              | Description |
|--------------------------------------|-------------|
| `git checkout -b <branch>`           | Create and switch to a new branch |
| `git commit -m "message"`            | Commit staged changes with a message |
| `git commit -am "message"`           | Add & commit changes in one step (tracked files only) |
| `git push -u origin <branch>`        | Push branch and set upstream to track remote |
| `git pull origin <branch>`           | Pull latest changes from remote branch |
| `git diff`                           | Show changes between working dir and index |
| `git log --oneline`                  | Compact commit history (one line per commit) |
| `git reset --hard HEAD~1`            | Completely undo the last commit |
| `git stash pop`                      | Reapply last stashed changes |
| `git branch -d <branch>`             | Delete a local branch |
| `git remote -v`                      | View remotes and their URLs |
| `git tag <v1.0>`                     | Create a lightweight tag |
| `git push origin --tags`             | Push all tags to remote |
| `.gitignore`                         | Specify files Git should ignore |

## Collaboration & GitHub-Specific
| Concept              | Description                                       |
|----------------------|---------------------------------------------------|
| Fork                 | Create your own copy of a repo                   |
| Pull Request (PR)    | Propose changes for merging into another branch  |
| Review               | Code review system in PRs                        |
| Merge Conflict       | Conflicts that arise when merging incompatible changes |
| GitHub Actions       | Automate CI/CD with workflows                    |
| Issues               | Bug tracking, feature requests                   |
| Labels               | Categorize issues/PRs                            |
| Milestones           | Group issues/PRs by goal                         |
| Projects             | Kanban boards for managing tasks                 |
| Releases             | Tag and package software versions                |
| GitHub Pages         | Host static sites from repo                      |
| Wikis                | In-repo documentation space                      |

## Security & Access
| Concept              | Description                                       |
|----------------------|---------------------------------------------------|
| `.gitignore`         | Specify files Git should ignore                  |
| SSH Keys             | Secure authentication for GitHub                |
| GPG Signatures       | Verify commit authenticity                       |
| Protected Branches   | Prevent force-pushes or unreviewed merges       |
| Personal Access Tokens (PAT) | API and Git access                     |
| Secrets (in Actions) | Secure variables for workflows                  |

## Advanced Topics
| Topic              | Description                                         |
|--------------------|-----------------------------------------------------|
| Submodules         | Link to other repos inside a repo                  |
| Hooks              | Custom scripts that trigger at Git lifecycle events|
| Git Bisect         | Binary search to find bug-causing commit          |
| Git Worktree       | Multiple working directories from the same repo   |
| Reflog             | Log of where HEAD and branches have been          |
| Squash             | Combine multiple commits into one                 |
| Tagging            | Mark specific points (e.g., v1.0.0)               |
| Blame              | See line-by-line author history                   |
| Archive            | Create zip/tar of a repo snapshot                 |



## Author

[Hashtech Innovations](https://hashtechinnovations.in)
