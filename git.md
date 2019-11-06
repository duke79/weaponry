[Commits per author](https://stackoverflow.com/questions/9839083/git-number-of-commits-per-author-on-all-branches)  
```
git shortlog -s -n --all --no-merges
```

[Lines by author](https://stackoverflow.com/questions/1265040/how-to-count-total-lines-changed-by-a-specific-author-in-a-git-repository)
```
git log --author="<authorname>" --oneline --shortstat
git log --author="<authorname>" --pretty=tformat: --numstat
```
