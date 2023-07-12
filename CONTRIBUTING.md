# Contribution Guide

## Git commit guideline

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

This repository is managed by `git-cz` to make it Commitizen-friendly. You should follow this way if you want to contribute here.

### How to commit

First of all, you should install some local packages to keep the documents' quality best.

The local packages in this repository are managed by `yarn`.

And you should use Git hooks to prevent accidents. This repository uses `husky` to manage Git hooks, and it will configure automatically when you install the packages.

1. Install the local packages and configure Git hooks.

```bash
yarn install
```

2. Commit

```bash
yarn commit
```

or use your local `git-cz` command.

```bash
git cz
```
