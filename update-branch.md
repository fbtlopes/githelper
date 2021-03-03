# Updating a branch with another branch (even master)

```bash
$ git checkout {branch source}
```
```bash
$ git pull
```
```bash
$ git checkout {branch destiny}
```
```bash
$ git pull
```
```bash
$ git merge {branch source}
```

Depending on your git configuration this may open vim. Enter a commit message, save, and quit vim: 
1. Press `a` to enter insert mode and append text following the current cursor position.
2. Press the **esc** key to enter command mode.
3. Type `:wq` to write the file to disk and quit.

This only updates your local feature branch. To update it on GitHub, push your changes.
```bash
$ git push
```
