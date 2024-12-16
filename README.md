# Gym-Git-Exercise-Solutions
* Bundle 2 Exercise 1
```bash
git branch ft/bundle-2   
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch
  dev
  ft/bundle-2
* main
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout ft/bundle-2
Switched to branch 'ft/bundle-2'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "create ft/bundle-2" 
[ft/bundle-2 c6c49ff] create ft/bundle-2
 1 file changed, 11 insertions(+)
 create mode 100644 services.html
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push --set-upstream origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 484 bytes | 161.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/josephine324/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
branch 'ft/bundle-2' set up to track 'origin/ft/bundle-2'.
```
