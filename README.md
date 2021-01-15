# git_commit_msg
Git Commit Message Conventions

Create a git commit template

Instructions at:
https://dev.to/timmybytes/keeping-git-commit-messages-consistent-with-a-custom-template-1jkm


VS Code Extension:
https://marketplace.visualstudio.com/items?itemName=vivaxy.vscode-conventional-commits


touch commit-conventions.txt
```
# ----------------------------------------------------------
# Header - (type): Brief description
# ----------------------------------------------------------
#   * feat         A new feature
#   * fix          A bug fix
#   * docs         Changes to documentation only
#   * style        Style/format changes (whitespace, etc.)
#   * refactor     Changes not related to a bug or feature
#   * perf         Changes that affects performance
#   * test         Changes that add/modify/correct tests
#   * build        Changes to build system (configs, etc.)
#   * ci           Changes to CI pipeline/workflow
# ----------------------------------------------------------


# ----------------------------------------------------------
# Body - More detailed description, if necessary
# ----------------------------------------------------------
#   * Motivation behind changes, more detail into how
# functionality might be affected, etc.
# ----------------------------------------------------------

# ----------------------------------------------------------
# Footer - Associated issues, PRs, etc.
# ----------------------------------------------------------
#   * Ex: Resolves Issue #207, see PR #15, etc.
# -----
```

```
git config --global commit.template path/to/your/file.txt
```

To open file at specific line
```
git config --global core.editor 'vim +14 +startinsert'
```
