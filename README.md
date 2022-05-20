# GIT TUTORIAL

## How to use Git correctly

First we have to create a local repository

Then we have to add files to that local repository

After that we have to create an online repositoy in **https://github.com/**

Finally, to sync both repositories we have to open our git CMD, that comes installed when we download git from **https://git-scm.com/downloads**, and put the following commands:

1. To init the link
```
git init
```

2. To add all files on the local repository
```
git add -A
```

3. To watch the status of the process
```
git status
```

4. To commit a version
```
git commit -m "Version Name"
```

5. To add the remote repository to the local repository
```
git remote add origin (repository link)
```

6. To push the file form local to remote repository
```
git push origin master
```
