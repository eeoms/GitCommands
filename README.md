## Some Git commands I'm saving just for my personal use because I forget them a lot.

Create a new repository on the command line
```bash
echo "# YOUR-REPOSITORY" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin master
```

Push an existing repository from the command line
```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git branch -M master
git push -u origin master
```

Clone an existing repository
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
