### git new repo

…or create a new repository on the command line

```bash
echo "# new1" >> README.md
git init
git add README.md
git commit -m "first commit"
git status
git branch -v
git branch -M main
git remote add origin git@github.com:Camaloff/new1.git
git push -u origin main

```

…or push an existing repository from the command line
```bash
git remote add origin git@github.com:Camaloff/new1.git
git branch -M main
git push -u origin main
```

1. Baikal