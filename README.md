# The commands for create, delete and rename a repo on github by terminal:

## 1- Convert a directory to a Git repository
```bash
git init
```

## 2- Stage the files
```bash
git add .
```

## 3- Commit the files
```bash
git commit -m "initial commit"
```

# For 2 next command "gh" should be installed and to intall it:
```bash
$ brew install gh
```

## 4- Authorise GitHub CLI (If you have never used the GitHub CLI tool before)
```bash
gh auth login
```

## 5- to create new repo with name "my-newrepo" as a public repo and push files (to create a private repo should use --private instead of --public)
```bash
gh repo create [my-newrepo] --public --source=. --remote=upstream --push
```