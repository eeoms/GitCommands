## Some Git commands I'm saving just for my personal use because I forget them a lot.

Create a new repository on the command line
```bash
echo "# YOUR-REPOSITORY" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git push -u origin main
```

Push an existing repository from the command line
```bash
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
git branch -M main
git push -u origin main
```

Clone an existing repository
```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```
