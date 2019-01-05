
## Getting Started
- get git 'https://git-scm.com/download/win'
- download Atom txt editor 'https://atom.io/'
- download NodeJs 'https://nodejs.org/en/'
- Make project directory
- Make a new project with npx create-react-app nameofproject
- Clone current project from github repo with git clone "http//..."
-  

## Most used git commands

- git checkout -b <new branch name>
- git checkout <existing branch name>
- git status
- git diff
- git push origin <branch name>
- git add <filename>
- git commit -m "<commit message>"
- git fetch origin
- git pull
- git merge <origin / <branch name>>
- git clone "name of project"

## Work Flow for git
- git status
- git checkout master
- git fetch origin
- git pull origin master
- create new feature branch
- git checkout -b branch_name
- make our changes to the code
- stage the files for commit
- git add filename
- commit the changes locally
- git commit -m "commit message"
- push changes up to the remote feature branch
- git push origin branch_name
- in github we want to create a pull request from the feature branch to master
- review the pull request changes and merge the feature branch to master
