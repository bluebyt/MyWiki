# Make a commit to master branch

### 1. Get latest changes
```
git pull origin main
```

### 2. Edit locally
```
mkdocs serve
```

### 3. Commit
```
git add .
```

```
git commit -m "Fix theme and palette configuration"
```

### 4. Push
```
git push origin main
```

### 5. Re-deploy the site
```
mkdocs gh-deploy
```

# Make a commit to a new branch

### 1. Switch to the new branch
```
git switch -c my-new-branch
```

### 2. Stage all changes
```
git add .
```

### 3. Commit all changes
```
git commit -m "Added Comment"
```

### 4. Push all changes
```
git push -u origin my-new-branch
```


