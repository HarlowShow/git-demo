# WWL - Git Basics

## Key Terms
*origin* - the main bit.
*remote* - your local bit (or someone else's local bit).

---

## Setting up Repos

### Cloning Repos

#### With HTTPS URL
`git clone [https repo name]`
#### Using Git CLI (TBC)
#### With SSH (TBC)

### Creating a repo (from command line)
[See here](https://www.youtube.com/watch?v=9p2d-CuVlgc)

### Getting Status Info
`git status`
_Make sure you're in the right directory first_

---

## Making Updates

### Staging Changes
`git add [filename]`
Stage a file
`git add .`
Stage all

### Committing Changes
`git commit -a -m "comment here"`
Commit all changes (-a), including a commit message(-m)git (you can also use `-am`)

### Pushing Changes
`git push origin main`
`main` being the branch name, which is the default origin branch

### Changing Branch
`git checkout [branch-name]`

---

## Branches

### List Current Branches
`git branch`

### Adding A Branch
`git branch [branch-name]`

### Switching Brances
`git checkout [branch-name]`

--- 

## Using Github Pages
Deploy from a branch called `gh-pages`, or set this up manually

---

## Useful Info/Help Commands
`git config --list`
See your config deets

`git log [-n]`
See commit history [/latest n commits]

`git remote [-v]`
Check out remote repositories