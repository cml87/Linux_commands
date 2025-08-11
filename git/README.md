```bash
# list all tracked files
$ git ls-files
```

```bash
# untrack a file

# remove a file from the index (staging area)
$ git rm --cached secret_file.txt
$ git commit -m "untrack a file"
$ git push
```