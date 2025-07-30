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

```
### - Exercise 2

```bash
git stash -u
git stash pop --index 1
git stash pop --index 0
```