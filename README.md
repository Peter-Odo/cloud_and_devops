<!-- VERSION CONTROL -->

# What is Version Control

Version control is a system that allows us (engineers or developers) to track and manage changes to a software code (source code) over time.

## Core concepts

### Snapshot of a project:

- Every time changes are committed, a snapshot of the current project state is saved.
- These snapshots allow users (engineers) view, compare, or roll back to any previous version.

### Collaboration:

- Multiple engineers can work on the same codebase (source code) without overwriting each other's changes.
- Branching and merging enable simultaneous work on different features or bug fixes.

### Change Tracking:

- Version control records who made what changes, when, and why
- This is essential for debugging and accountability.

## Benefits of Git

- Decentralized Nature: Each contributor has a full copy of the project (repository), including the entire history. Work can continue offline and changes can be synced later.

- Performance: Git is optimized for speed, enabling quick branching, merging and history lookups.

- Collaborations: Features like branches, pull requests, merging options simplify team work.

- Support Automation: Integrates seamlessly with CI/CD pipelines.

## Git Basics

#### Setting up

- Linux:

```
sudo apt-get install git
```

- Mac:

```
brew install git
```

- Windows:

```
https://git-scm.com
```

#### Core commands

- Initialize a repository (project, folder)

```
git init
```

- Check Repository Status

```
git status
```

- Staging Changes

```
git add <file_name>         # Stage a specific file
git add .                   # Stage all changes
```

- Commit Changes

```
git commit -m "Describe your changes"
```

- Push changes

```
git push origin <branch_name>
```

#### Collaborating with GIT (BRANCHES)

- What is a branch?: A branch is a pointer to a specific commit, allowing us to work features or fixes independently of the main codebase

- Main branch (main, master, development, production): The default branch for production-ready code

#### Workflow

- create a branch

```
git branch <branch_name>
```

- switch to the Branching

```
git checkout <branch_name>
```

### This is from the new branch
