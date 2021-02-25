Steps to initialize a new repository:
1. Use GUI to create a folder that will store a local copy of the repository
2. Open Git Bash and `cd` into the created folder
3. pwd to double check current location
4. Use touch to create necessary files (usually at least a README.md and an index.html file)
5. ls to douoble check that necessry files have been created `code .` to enter VS Code and then open a new terminal
6. Initialize a repo using `git init`
7. Stage and commit the newly created files using `git add .` and `git commit -m "..."`
8. Go to Github and open a new repository
9. Create the master branch using `git branch -M main`
10. Set the main branch as the remote origin using `git remote add origin <URL>`
11. Set the upstream using `git push -u origin main`
12. Create and move to a new branch using `git checkout -b dev`
13. Use `git status` to double check you're good to go
14. Make some changes (anywhere will do), before staging and committing them
15. Set the upstream again to dev using `git push --set-upstream origin dev`
16. Go to Github to make a pull request and merge the pr into main
17. Go to Netlify to create a deploy link
18. You're now good to go!

[![Netlify Status](https://api.netlify.com/api/v1/badges/34367cdb-e1b4-4052-ad23-40bdc221b17f/deploy-status)](https://app.netlify.com/sites/elwins-test-repo/deploys)