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
 echo !>home.html
  26 echo .>home.html
  27 echo '.'>home.html
  28 git stash
  29 git stash pop
  30 git stash -u
  31 git stash list
  32 git stash apply
  33 git stash clear
  34 git stash list
  35 git stash -u
  36 echo .>about.html
  37 echo '.'>about.html
  38 git stash -u
  39 echo '!'>team.html
  40 git stash -u
  41 git stash show
  42 git stash list
  43 git stash pop stash@{1}
  44 git stash pop
  45 git stash pop
  46 git stash -u
  47 git stash pop
  48 git stash pop
  49 git stash pop
  50 git stash pop
  51 git stash list
  52 git stash pop stash@{1}
  53 git stash pop --index 1
  54 git stash pop --index 0
  55 git stash list
  56 git stash pop --index 2
  57 git add -A
  58 git commit -m "Bundle 1 Exercise 2"
  59 git stash apply
  60 git add -A
  61 git commit -m "Bundle 1 Exercise 2"
  62 git push origin -o main

```