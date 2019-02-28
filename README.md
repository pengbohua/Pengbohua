Just to remind myself
<<<<<<< HEAD
For every update, run this cmd, do NOT clear the path 'CNAME' and 'git'.
=======
For every update, run this cmd in the path of '_site', do NOT clear the path 'CNAME' and 'git'.
>>>>>>> 0bc18457fd945f2ab01c90a0e30f5aeec8c698a8
```
find . -maxdepth 1 ! -name '_site' ! -name '.git' ! -name 'CNAME' ! -name '.gitignore' -exec rm -rf {} \;
```

