Just to remind myself
For every update, run this cmd in the path of '_site', do NOT clear the path 'CNAME' and 'git'.
```
find . -maxdepth 1 ! -name '_site' ! -name '.git' ! -name 'CNAME' ! -name '.gitignore' -exec rm -rf {} \;
```

