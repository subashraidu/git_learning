Git Learning

✅ Core Git Concepts (Fundamental)

What is Git? – Distributed version control system.

Repositories

Local vs Remote

git init, git clone

Basic Commands

git status

git add, git commit

git push, git pull, git fetch

.gitignore – Ignoring files/folders

Branches

git branch, git checkout, git switch

Creating and managing branches

Merging & Rebasing

git merge

git rebase

Fast-forward vs non-fast-forward merges

Viewing History

git log, git diff, git show

Aliases and formatting logs

Tags

git tag, version tagging

Lightweight vs annotated tags

🚀 Intermediate Git Concepts (For Workflow & Collaboration)

Branching Strategies

Git Flow

GitHub Flow

Trunk-Based Development

Pull Requests / Merge Requests

Code reviews, approvals, automation triggers

Conflict Resolution

Detecting, resolving, and avoiding conflicts

Stashing

git stash, git stash pop, temp work

Cherry Picking

git cherry-pick selective commits

Reverting and Resetting

git revert

git reset (soft, mixed, hard)

git reflog for recovering lost commits

🔧 Advanced Git Concepts (For Automation & Recovery)

Git Hooks

Pre-commit, pre-push, post-merge hooks

Automating code checks/tests

Submodules and Subtrees

Managing code across multiple repos

Git Internals

.git directory structure

Git objects: blobs, trees, commits, tags

Detached HEAD and Recovery

Working in detached state

Using reflog to recover lost commits

Squashing Commits

git rebase -i

Clean up commit history

Signing Commits

git commit -S – GPG key signing for verified commits

🔁 Git in CI/CD and DevOps Workflows

Git as a Trigger in CI/CD

Pipeline triggered by branch push/tag

Merge request events

Versioning with Tags in Pipelines

Deployments based on tag versions

GitOps Principles

Git as the source of truth

Repos storing declarative infra (e.g., Kubernetes manifests)

Rollback Strategies

Using tags/branches to revert deployments

Git Integration with CI/CD Tools

GitHub Actions, GitLab CI, Jenkins, CircleCI, etc.

Git in Infrastructure as Code (IaC)

Store Terraform, Ansible, Helm charts in Git

Automate validation, testing, and deployment

🔐 Security & Best Practices

SSH vs HTTPS Authentication

Managing Access to Repositories

Personal Access Tokens

Git Credential Storage

Secure Handling of Secrets (DON’T commit secrets)

🧠 Optional/Expert Concepts

Rewriting History

git rebase, git filter-branch, git reset

Used with caution in team environments

Large File Storage (LFS)

Handling binary/large files with Git LFS

Git Aliases

Create shortcuts for repetitive commands
