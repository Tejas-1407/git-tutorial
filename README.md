# Git Tutorial

A small repository for learning Git and GitHub step by step.

## Start here

Run these commands in this folder:

```bash
git init
git add .
git commit -m "Initial commit"
```

Then create an empty repository on GitHub and connect it:

```bash
git branch -M main
git remote add origin <your-repository-url>
git push -u origin main
```

## Practice workflow

1. Edit `notes.md`.
2. Check what changed:

   ```bash
   git status
git diff
   ```

3. Stage and commit the change:

   ```bash
   git add notes.md
git commit -m "Update learning notes"
   ```

4. Push it to GitHub:

   ```bash
   git push
   ```

## Useful commands

```bash
git log --oneline
git branch
git remote -v
```
