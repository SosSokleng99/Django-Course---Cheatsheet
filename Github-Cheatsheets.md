# How to use Github for Source Code Management(SCM)

### 1. Create a new repository on GitHub.com. and Intall Git
### 2. At the top of your repository on GitHub.com's Quick Setup page, click  to copy the remote repository URL.
### 3. Navigate the current working directory to your local project.
### 4. To add the URL for the remote repository where your local repository will be pushed, run the following command. Replace REMOTE-URL with the repository's full URL on GitHub.
```bash
git remote add origin "REMOTE-URL-GitHub"
```
> To Switch from connected Github Repository to another Specific Github Repository URL
```bash
git remote set-url origin "REMOTE-URL-GitHub"
```
### 5. To verify that you set the remote URL correctly, run the following command.
```bash
git remote -v
```

### 6. Create NEW-BRANCH on GitHub Repos to push code to.
```bash
git checkout -b "NEW-BRANCH-NAME"
```

> To Switch to a Specific Branch
```bash
git checkout "BRANCH-NAME"
```

### 7. To add all change to the new BRANCH
```bash
git add .
```


### 8. Check and Verify Adding Change to NEW-BRANCH
```bash
git status
```


### 9. Commit the changed files with Comment
```bash
git commit -m "Did Something"
```


### 10. Finally, Push the branch to GitHub
```bash
git push origin skeleton_website
```

