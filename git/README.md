```bash
# list all tracked files
$ git ls-files
```

```bash
# untrack a file

$ echo "secret_file.txt" >> .gitignore
# remove a file from the index (staging area)
$ git rm --cached secret_file.txt
# notice we don't do a git add, cuz the index is already 
# in the state we want to commit (a file have been removed from the index) 
$ git commit -m "untrack a file"; git push 
```