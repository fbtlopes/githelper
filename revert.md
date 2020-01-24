# Revert

```bash
$ git reset --hard 0682c06  # Use the SHA1 of the revision you want to revert to HEAD is now at 0682c06 G3
$ git reset --soft HEAD@{1}
$ git commit -m "Reverting to the state of the project at 0682c06"
```
