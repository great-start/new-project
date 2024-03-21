## new-project

### Create dir "new-project"
```
$ mkdir new-project
```

### Move to dir
```
$ cd new-project
```

### Initialize repo
```
$ git init
```

### Rename default branch to "main" (if it is not "main")
```
$ git branch -m main
```

### Create file README.md
```
$ touch README.md
```

### Init first commit at branch "main"
```
$ git add README.md
$ git commit -m "init"
```

### Create public repository at GitHub called - "new-project"

### Connect local repository with remote public
```
$ git remote add origin https://github.com/<GitHub_username>/new-project.git
```

### Push all local changes (you should be able to enter name and token)
```
$ git push -u origin main
```

### Create new branch "development" from "main" and switch to it
```
$ git switch -c development
```

### Add new data to README.md and save changes

### Check README.md for new changes to be commited
```
$ git status
```

### Init first commit in "development" branch
```
$ git commit -a -m "init_development_commit"
```

### Publish branch "development" (you should be able to enter name and token)
```
$ git push -u origin development
```

### Merge changes from branch "development" to "main"
```
$ git switch main
$ git merge development
```

### Push all local changes (you should be able to enter name and token)
```
$ git push origin main
```

### Check status
```
$ git status
```
