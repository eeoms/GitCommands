## Some Git commands I'm saving just for my personal use because I forget them a lot.

Create a new repository on the command line
```bash
echo "# GitCommands" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/eeoms/GitCommands.git
git push -u origin main
```

Push an existing repository from the command line
```bash
git remote add origin https://github.com/eeoms/GitCommands.git
git branch -M main
git push -u origin main
```
