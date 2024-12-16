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

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\HP\OneDrive\Desktop\Git Exercises>   git push --set-upstream origin main
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/josephine324/Gym-Git-Exercise-Solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git pull origin main --allow-unrelated-histories
From https://github.com/josephine324/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Merge made by the 'ort' strategy.
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> 
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git status
On branch main
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises>   git push --set-upstream origin main
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (5/5), 704 bytes | 234.00 KiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/josephine324/Gym-Git-Exercise-Solutions.git
   4a449f6..94786f0  main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch -b dev
error: unknown switch `b'
usage: git branch [<options>] [-r | -a] [--merged] [--no-merged]
   or: git branch [<options>] [-f] [--recurse-submodules] <branch-name> [<start-point>]
   or: git branch [<options>] [-l] [<pattern>...]
   or: git branch [<options>] [-r] (-d | -D) <branch-name>...
   or: git branch [<options>] (-m | -M) [<old-branch>] <new-branch>
   or: git branch [<options>] (-c | -C) [<old-branch>] <new-branch>
   or: git branch [<options>] [-r | -a] [--points-at]
   or: git branch [<options>] [-r | -a] [--format]

Generic options
    -v, --verbose         show hash and subject, give twice for upstream branch
    -q, --quiet           suppress informational messages
    -t, --track[=(direct|inherit)]
                          set branch tracking configuration
    -u, --set-upstream-to <upstream>
                          change the upstream info
    --unset-upstream      unset the upstream info
    --color[=<when>]      use colored output
    -r, --remotes         act on remote-tracking branches
    --contains <commit>   print only branches that contain the commit
    --no-contains <commit>
                          print only branches that don't contain the commit
    --abbrev[=<n>]        use <n> digits to display object names

Specific git-branch actions:
    -a, --all             list both remote-tracking and local branches
    -d, --delete          delete fully merged branch
    -D                    delete branch (even if not merged)
    -m, --move            move/rename a branch and its reflog
    -M                    move/rename a branch, even if target exists
    -c, --copy            copy a branch and its reflog
    -C                    copy a branch, even if target exists
    -l, --list            list branch names
    --show-current        show current branch name
    --create-reflog       create the branch's reflog
    --edit-description    edit the description for the branch
    -f, --force           force creation, move/rename, deletion
    --merged <commit>     print only branches that are merged
    --no-merged <commit>  print only branches that are not merged
    --column[=<style>]    list branches in columns
    --sort <key>          field name to sort on
    --points-at <object>  print only branches of the object
    -i, --ignore-case     sorting and filtering are case insensitive
    --recurse-submodules  recurse through submodules
    --format <format>     format to use for the output

PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch
* main
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout -b dev
Switched to a new branch 'dev'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout -b test
Switched to a new branch 'test'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout dev
Switched to branch 'dev'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch -d test
Deleted branch test (was 94786f0).
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "Delete test branch"
On branch dev
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git add .
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "Deleting test branch"
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout dev
Switched to branch 'dev'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout test
error: pathspec 'test' did not match any file(s) known to git
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git checkout dev 
Already on 'dev'
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git commit -m "deleting test branch"
On branch dev
nothing to commit, working tree clean
PS C:\Users\HP\OneDrive\Desktop\Git Exercises> git branch
* dev
  main
  ```