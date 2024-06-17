# Git

# Settings

- Change author and e-mail

```
git config --global user.name # print current global setting
# change global setting
git config --global user.name "CSRedRat"
git config --global user.email "csredrat@gmail.com"
# change stting for current repo
git config user.name "CSRedRat"
git config user.email "csredrat@gmail.com"
```

- Save credentials permanent
```
git config credential.helper store
```

# Undo changes

- Change commit author

```
git rebase -i -p <some HEAD before all of your bad commits> # if you have only one commit you may don't exec this command, you alredy ammend last commit
git commit --amend --committer-date-is-author-date # keep the date same as before
git commit --amend --author="Ivan Smith <ivan@smith.org>" --no-edit
git rebase --continue
# git push --force # Caution! you lost git history on origin git server, backup data
```

Single commit without rebase:

```
git commit --amend --author "Ivan Smith <ivan@smith.org>"
git -c user.name="New Author Name" -c user.email=email@address.com commit --amend --reset-author
```

# Aliase

- [gitalias](https://github.com/GitAlias/gitalias)