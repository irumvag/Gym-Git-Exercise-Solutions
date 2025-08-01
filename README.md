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
### - Exercise 1
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
### -Exercise 2
```bash
 git checkout main
 git add .\services.html
 git commit -m "The service html changed"
 git push origin main
 git push origin main
 git push origin main
 git push -o origin main
 git push -o origin main
 git push -o origin main
 git push origin main
 git pull
 git push origin main
 git pull
 git status
 git add -A
 git commit -m "The service html changed"
 git push origin main
 gh help
 gh --help
 git gh
 clear
 git add -A
 git commit -m "The service html changed"
 git push origin main
```
## Bundle 3
### - Exercise 1
```bash
 git add .
 git commit -m "Bundle 2 Exercise 2 done"
 git push origin main
 git checkout -b ft/team-page
 git branch
 git stats
 git status
 git add .\team.html
 git commit -m "The team html file added"
 git push origin ft/team-page
 git checkout main
 git status
 git checkout -b ft/contact-page
 git checkout ft/team-page
 git status
 git log --oneline
 git checkout -b ft/contact-page
 git checkout  ft/contact-page
 git cherry-pick 6476603
 git status
 add .\contact.html
 git commit -m "Contact us page added"
 git checkout ft/contact-page
 git add .\contact.html
 git commit -m "Contact us page added"
 git push --set-upstream origin ft/contact-page
 git checkout -b ft/faq-page
 git add .\faq.html
 git commit -m "faq html created!"
 git push origin ft/faq-page
 git log --oneline
 git revert 3bb2955
 git push origin ft/faq-page
```
### - Exercise 2
```bash 
  git checkout ft/faq-page
  git checkout -b ft/home-page-redesign
  git checkout main
  git add -A
  git commit -m "Home page redesigned"
  git push origin main
  git pull
  git push origin main
  git checkout ft/home-page-redesign
  git status
  git rebase origin/main
  git add -A
  git commit -m "Homepage redesign"
  git push --set-upstream origin ft/home-page-redesign
```
## Bundle 4
### - Exercise 1
```bash
 git checkout main
 git remote add git-copy https://github.com/irumvag/Git-Exercises... 
 git add .
 git commit -m "home changed"
 git push origin main
 git push git-copy main
```
### - Exercise 2
```bash

```