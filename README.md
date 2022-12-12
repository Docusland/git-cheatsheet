# Git Cheatsheet

## CREATE

Clone existing repository

```shell
git clone git@github.com:user/repo.git
```

Create new repository

```shell
git init
```

## BRANCHES & TAGS

Create a new branch

```shell
git branch <branch_name>
```

```mermaid
gitGraph
    commit
    commit
    branch branch_name
    commit
```

List all branches

```shell
git branch
```