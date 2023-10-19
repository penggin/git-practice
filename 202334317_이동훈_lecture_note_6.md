# 202334317_이동훈_lecture_note_6

# Git commands

## configurations

### config level

- system (—system)
    - Affects all users and repo on the system
- user (—global)
    - Affects all repo of a current user
- local (—local)
    - Affects to the current repo

### command

```bash
git config --list
git config [scope opt] [option] <value>
```

## initializing

`git init`

initializing a repo in an existing directory.

## Check repo status

`git status`

## Adding New file to be tracked

`git add [file name]`

## Remove tracked file

`git rm --cached [filename]`

## ignore file

by editing `.gitignore` file, you can ignore files.

## commit changes

`git commit -m [message]`

## change branch name

`git branch -m [before] [after]`