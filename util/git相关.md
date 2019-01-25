#### total lines of you project:

```
find . -name "*.m" -or -name "*.h" |xargs grep -v "^$"|wc -l
```

