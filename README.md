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
