## GIT

# Git is a distributed version control system (VCS) that helps track changes in source code, collaborate with teams, and manage different versions of a project efficiently.

Key points:
Every developer has a full copy of the repository (not just a central one).
You can track history, revert mistakes, and experiment safely with branches.
It’s the backbone for tools like GitHub, GitLab, and Bitbucket.

# Why is Git useful for a DevOps Engineer?
DevOps = Development + Operations. Git sits at the center of this collaboration. Here’s how:

1. Source Code Management (SCM)
DevOps engineers often manage not just app code but also infrastructure code (Terraform, Ansible, Helm, Kubernetes YAML).
Git ensures everything is version-controlled, reproducible, and auditable.

2. Collaboration
Teams can work on the same project simultaneously using branches.
Git workflows (like GitFlow, trunk-based) help manage releases and hotfixes.

3. CI/CD Pipelines
Tools like Jenkins, GitHub Actions, GitLab CI, and CircleCI integrate directly with Git.
A new commit/push can automatically trigger builds, tests, and deployments.

4. GitOps
A modern DevOps practice where Git is the single source of truth for infrastructure and deployments.
Tools like ArgoCD and Flux continuously sync Git with Kubernetes clusters.

5. Audit & Rollback
If something breaks, you can quickly roll back to a previous commit/tag.
Provides a clear audit trail of who changed what and when.

Git is the foundation of DevOps workflows. Without Git, CI/CD pipelines, GitOps, collaborative coding, and version-controlled infrastructure wouldn’t exist.

6. Branching & Experimentation

DevOps engineers can test infrastructure or configuration changes in feature branches before merging to production.
