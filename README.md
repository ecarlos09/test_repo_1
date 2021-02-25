Steps to initialize a new repository:
[] Use GUI to create a folder that will store a local copy of the repository
[] Open Git Bash and cd into the created folder
[] pwd to double check current location
[] Use touch to create necessary files (usually at least a README.md and an index.html file)
[] ls to douoble check that necessry files have been created
[] code . to enter VS Code and then open a new terminal
[] Initialize a repo using git init
[] Stage and commit the newly created files using git add . and git commit -m
[] Go to Github and open a new repository
[] Create the master branch using git branch -M main
[] Set the main branch as the remote origin using git remote add origin <URL>
[] Set the upstream using git push -u origin main
[] Create and move to a new branch using git checkout -b dev
[] Use git status to double check you're good to go
[] Make some changes (anywhere will do), before staging and committing them
[] Set the upstream again to dev using git push --set-upstream origin dev
[] Go to Github to make a pull request and merge the pr into main
[] Go to Netlify to create a deploy link
[] You're now good to go!

[![Netlify Status](https://api.netlify.com/api/v1/badges/34367cdb-e1b4-4052-ad23-40bdc221b17f/deploy-status)](https://app.netlify.com/sites/elwins-test-repo/deploys)