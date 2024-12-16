# Gym-Git-Exercise-Solutions
* Bundle 1 Exercise  1( HISTORY )
```bash
 C:\Users\HP\OneDrive\Desktop\Git Exercises> ls 


    Directory: C:\Users\HP\OneDrive\Desktop\Git Exercises


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
-a----        2024-12-16   7:40 PM            241 index.html


PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "rename a branch"
On branch main
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push origin main
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/josephine324/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git pull origin main
From https://github.com/josephine324/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git remote add origin https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
error: remote origin already exists.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch
* main
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push origin main
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/josephine324/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git pull origin main
From https://github.com/josephine324/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git merge
fatal: No remote for the current branch.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git statul
git: 'statul' is not a git command. See 'git --help'.

The most similar command is
        status
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git init
Reinitialized existing Git repository in C:/Users/HP/OneDrive/Desktop/Git Exercises/.git/
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git pull origin main
From https://github.com/josephine324/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push origin 
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

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
```bash
* Bundle 2 Exercise 2
 git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "services page modified"
[main 96f9bb0] services page modified
 1 file changed, 1 insertion(+), 1 deletion(-)
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push 
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 335 bytes | 167.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
   910e25f..96f9bb0  main -> main
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout ft/srvice-redesign 
Switched to branch 'ft/srvice-redesign'
Your branch is up to date with 'origin/ft/srvice-redesign'.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git merge main
fatal: You have not concluded your merge (MERGE_HEAD exists).
Please, commit your changes before you merge.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git pull origin main
error: You have not concluded your merge (MERGE_HEAD exists).
hint: Please, commit your changes before merging.
fatal: Exiting because of unfinished merge.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "resolving conflicts"
[ft/srvice-redesign d5cf1b1] resolving conflicts
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git push
Enumerating objects: 1, done.
Counting objects: 100% (1/1), done.
Writing objects: 100% (1/1), 221 bytes | 221.00 KiB/s, done.
Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
   f52fc6c..d5cf1b1  ft/srvice-redesign -> ft/srvice-redesign
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> 
