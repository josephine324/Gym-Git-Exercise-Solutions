# Gym-Git-Exercise-Solutions
# BUNDLE 1 EXERCISE 1
* Create a project folder & initialize git
```bash
mkdir Git Exercises
git init
```
* Make changes to the project (add files and contents)
* Rename your main branch from master to main (If your branch name is already main then rename it to master and then back to main)
```bash
git branch -M main
```
* Stage your changes and commit them
* Create a Github repo and connect it with your project
```bash
git remote add origin https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
```
* Push your changes to GitHub
* Create a new branch dev
```bash
git checkout -b dev
```
* From dev create another branch test
```bash
git branch test
```
* Go back to the dev branch and delete the test branch
```bash
git checkout dev
git branch -d test
```
# Exercise 2
* Create a new home.html file, add some html changes and save them
* Stash save your current changes
```bash
git stash -u
```
* Repeat the same process for a new about.html page and stash save your changes
* Repeat the same process for a new team.html page and stash save your changes
* Using stash pop restore the changes of the about.html page
```bash
git stash pop [<stash@{n}>]
```
* With the help of an index use stash pop bring back the home.html page changes
* Commit the current changes and push themmmit the current changes and push them
* Reset the current changes using git reset and go back to the changes without the team.html page
```bash
git reset team.html
```
# BUNDLE 2 Exercise 1
* Create a new branch named ft/bundle-2 
```bash
git branch ft/bundle-2 
```
* Add new changes to your project. create a new page named services.html and add some changes
* Commit your changes and create a Pull Request against the main branch in your github repository
* Request a review and make sure your Pull request gets merged (Look for someone to merge your PR)
# Exercise 2
* Checkout your main branch and pull the latest changes
* Create a new branch named ft/service-redesign
```bash
git branch ft/service-redesign
```
* Add new changes to the service.html page
* commit and push them
* create a new PR for your changes
* go back to your main branch and add again new changes to your service.html page, you can add different changes but make sure to affect the same part(line of code) as you did in the other PR
* Commit and push those changes
* Now go back to the Github PR you had created for the ft/service-redesignbranch, you will then see that you have conflicts with the main branch
* In your project checkout the ft/service-redesign branch
```bash
git checkout ft/service-redesign 
```
* Compare the ft/service-redesignwith the main branch using git diff and observe the changes
* Using git merge, merge the main branch with ft/service-redesign branch and commit and push you changes again

# BUNDLE 3 EXERCISE 1
* Create a new branch named ft/team-page
```bash
git branch ft/team-page
```
* Create a new html page named team.html and add some changes
* commit and push those changes
* Create a new PR for the changes
* Go back to main branch (checkout the main branch)
```bash
git checkout main
```
* Create new branch named ft/contact-page
```bash
git branch ft/contact-page
```
* Go back to the ft/team-page 
```bash
git checkout ft/team-page 
```
* With the help of git log look for the last commit and copy its hash
```bash
git log
```
* Checkout again ft/contact-page using git cherry-pick get the changes from the last commit on the ft/team-page branch.
```bash
git checkout ft/contact-page 
git cherry ft/contact-page ft/team-page
```
* Add new changes for the contact page and commit, push them
* Create a new PR for the contact page
* From the ft/contact-page branch create a new branch called ft/faq-page
```bash
git branch  ft/faq-page
```
* Create a new faq.html page and add some changes there
* Commit and push those changes
* Using git revert, revert the changes of the last commit of the ft/team-page branch. (use the commit hash you copied earlier)
```bash
git revert 
```
* Push the changes and create a new PR







