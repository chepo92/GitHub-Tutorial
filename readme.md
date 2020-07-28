# Git essential commands 

## Start version tracking
git init

## Clone a repo
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY

## Add files 
git add --all

## Add another repo as subfolder 
git submodule add https://github.com/chaconinc/DbConnector

See: https://git-scm.com/book/en/v2/Git-Tools-Submodules

## See status
git status

## Configure Username 
git config --global user.name "<Your-Full-Name>"

## Configure Email
git config --global user.email "<your-email-address>"

## commit 
git commit -m "Commit message"

## Push 
git push

## Pull 
git pull

## Remove version tracking
rm -rf .git
