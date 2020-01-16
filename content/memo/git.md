---
title: "Git memo"
date: 2020-01-15T14:47:08+01:00
draft: true
toc: false
images:
tags: 
  - memo
  - git
---

## Repository

### Create repository
```shell
mkdir myrepo && cd myrepo
git init
```

### Clone repository
```shell
Local : git clone path_to_repo
Remote : git clone username@host://path_to_repo
```

## Files

### Add file
```shell
git add filename
or 
git add *
```

### Commit changes
```shell
git commit -m "Commit message"
```

### Files status
```shell
git status
```

## Branchs

### Branchs list
```shell
git branch -a
```

### Create branch

```shell
# 2 lines: create and checkout new branch
git branch new_branch_name
git checkout new_branch_name

# 1 line: create and checkout
git checkout -b new_branch_name
```