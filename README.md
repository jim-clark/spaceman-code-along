## To sync your code with the repo's

Run the following two commands in terminal:
```
git fetch --all
git reset --hard origin/main
```

The above commands will result in your local repo mirroring the remote's code exactly.  Any changes you've made to files, committed or not, will be replaced by the files in the remote (origin).

IMPORTANT:  Do not sync with unsaved changes on any files - this will cause havoc.