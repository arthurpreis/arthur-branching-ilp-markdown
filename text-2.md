# Release Plan: Campus App

## Goal

The team is preparing **version 1.0** for release on *Friday*.

## Tasks

- [x] Preparation completed
    - [x] Clone repository
    - [x] Update local `main`
- [ ] Implementation still open
    - [ ] Test navigation
    - [ ] Check profile page
    - [ ] Update README

## Team overview

| Area | Responsible | Status |
| ---- | ----------- | ------ |
| Navigation| Aylin | done |
| Profile page | Ben | in progress |
| Tests | Team | open |

## Planned workflow

1. **Update main**
```
git switch main
git pull
```
2. Create working branch
```
git switch -c release-check
```
3. Review and save changes
```
git status
git add .
git commit -m "Prepare release"
```

> **Note**: Avoid direct changes on `main`. Use a separate branch for every task.

### Documentation

[GitHub Flow](https://docs.github.com/en/get-started/using-github/github-flow)