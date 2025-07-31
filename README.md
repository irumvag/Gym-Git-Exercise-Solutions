# Git Exercises 
## Bundle 1
### - Exercise 1

```bash

cd Gym_Git_Exercise_Solutionse_Solutions
echo .>README.m
git init       
git branch -m master main 
git status
git branch -m main master
git status     
git add --all  
git commit -m "First commit"
git branch -M main
git remote add origin https://github.com/irumvag/Gym-Git-Exercise-Solutions.git
git push -u origin main
git branch dev
git checkout dev
git checkout -b test
git checkout dev
git branch -d test
git push origin --delete test

```
### - Exercise 2

```bash
  echo '.'>home.html
  git stash -u
  git stash list
  git stash -u
  echo '.'>about.html
  git stash -u
  echo '!'>team.html
  git stash -u
  git stash show
  git stash list
  git stash pop
  git stash pop
  git stash list
  git stash pop stash@{1}
  git stash pop --index 1
  git stash list
  git stash pop --index 2
  git add -A
  git commit -m "Bundle 1 Exercise 2"
  git stash apply
  git add -A
  git commit -m "Bundle 1 Exercise 2"
  git push origin -o main
  git log --oneline
  giy reset --hard 38fdd8d

```
## Bundle 2
### Exercise 1
```bash
git branch ft/bundle-2
git branch
echo '!'>services.html
git commit -m "service file added"
git add services.html
git commit -m "service file added"
git push origin ft/bundle-2
git checkout ft/bundle-2
git status
git push --set-upstream origin ft/bundle-2
git push
git status
```
### Exercise 2
```bash

```