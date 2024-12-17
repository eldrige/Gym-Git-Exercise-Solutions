# Git Execices

This repo contains the answers to the git exercices

## Exercice One

- git init
- git branch -m main
- git branch -m master
- git add .
- git commit -m "changes"
- git remote add origing repo_name
- git push -u origin master
- git switch -c dev
- git switch -c test
- git switch dev
- git branch -D test

## Exercice One (Bundle Two)

- git switch -c ft/bundle-2
- git add .
- git commit -m "bundle branch"
- git push -u origin ft/bundle-2

## Exercice Two (Bundle Two)

- git switch main
- git switch -c ft/service-redesign
- git add .
- git commit -m "redesign branch"
- git push
- git switch main
- git add .
- git commit -m "new changes"
- git push
- git switch ft/service-redesign
- git diff main..ft/service-redesign
- git merge main
- git push

## Exercice Three (Bundle Two)

- git switch main
- git switch -c ft/team-page
- git add .
- git commit -m "team branch"
- git push
- git switch main
- git switch -c ft/contact-page
- git switch ft/team-page
- git log
- git cherry-pick commit_hash
- git add .
- git commit -m "used cherry pick"
- git push
- git switch -c ft/faq-page
- git add .
- git commit -m "some changes"
- git revert commit_hash
