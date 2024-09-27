# How to create "Branch" in Github for Source Code Management(SCM)


### 1. Create NEW-BRANCH on GitHub Repos to push code to.
```bash
git checkout -b "NEW-BRANCH-NAME"
```

> To Switch to a Specific Branch
```bash
git checkout "BRANCH-NAME"
```

### 2. To add all change to the new BRANCH
```bash
git add .
```


### 3. Check and Verify Adding Change to NEW-BRANCH
```bash
git status
```


### 4. Commit the changed files with Comment
```bash
git commit -m "Did Something"
```


### 5. Finally, Push the branch to GitHub
```bash
git push origin "BRANCH-NAME"
```

