# AssignmentGITHUBrepo
GitHub is used to store the Data files codes in cloud based
- Where as Google driver, but for code github
- We can access codes from anywhere, at any time
- Helps you manage versions of your code, You can go back to a previous version if something breaks.
- Work with teammates on the same project.
- To Showcase the work
- Join open-source communities.
- Learn from real-world code and give back by contributing.
  # Git Commands To store in repository
- Command used to add a remote repository:
    - git remote add origin repo URL
    - git remote add origin https://github.com/username/Reponame.git
    - EX: https://github.com/swathi-T3/AssignmentGITHUBrepo.git

- Check if the remote repository is linked successfully:
    - git remote -v
    - origin  https://github.com/username/Reponame.git (fetch)
    - origin  https://github.com/username/Reponame.git (push)

- Command to push your code to GitHub:
    - git push -u origin main

- What branch was pushed to the remote repository?
    - By looking at the branch name used in the git push command ex- main or master

- How can you view the changes in your GitHub repository?
    - By clicking on the "Commits" tab to see what was pushed.
    - or click on specific files to view their current contents.
 
- Start a New Local Repository
```git init```
- Connect Local Repo to GitHub
```git remote add origin https://github.com/your-username/your-repo-name.git```
- Rename Current Branch to main
```git branch -M main```
- Check Status of Changes
```git status```
-  Stage Changes (Add to Staging Area)
```
git add .
git add filename.extension
```
- Commit Staged Changes
```git commit -m "Your commit message"```
- Push Code to GitHub
```
git push -u origin main
git push
```
- Pull Latest Code from GitHub
```git pull origin main```
- Clone a Repository from GitHub
```git clone https://github.com/username/repo-name.git```
- See Commit History
```git log```
- Undo All Local Changes - Dangerous
```git reset --hard```


