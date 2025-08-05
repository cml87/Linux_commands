```bash
# For every directory X in the current directory, create file X.md inside
# xargs -n 1  ->  process one item at a time 
ls -p | grep / | tr -d / | xargs -n 1 sh -c 'touch $1/$1.md' _
```
