# My Git Cheatsheet

## Creating a Git Repo

In the folder you want to create a repo, do the following command in terminal.

``` 
git init
```

**Always check to ensure you're not already in a repo by using ```git status```**

---

## Adding Files to Staging

Staging is files that are being tracked to be committed.

Use `git status` to see which files are untracked(red) or in staging (green)

``` 
git status
```

Three ways to add files to staging: 

- Add one file at a time with: `git add <filename>`
- Add all files in the repo with: `git add -A`
- Add all files in my current folder with: `git add .`

---

## Committing Files to Our Repo

```
git commit -m "some random text, something descriptive"
```

**If you forget the -m, you'll end up in vim, to exit - type ":wq"**

---

## Looking at our Commit History

```
git log
```

```
git log --oneline
```

---

## Working with Remotes (Enterprise, GitHub, GitLab, BitBucket)

- To add a remote, do: `git remote add <name> <url>`
- To see a list of remotes, do: `git remote -v`
- To push the code, do: `git push <remoteName> <branchName>`
- To see your current branch `git branch`