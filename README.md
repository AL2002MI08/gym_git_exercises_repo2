# Bundle 1
## exercise 1
```
PS C:\Users\alexa\Desktop\git_exercise> git init
Initialized empty Git repository in C:/Users/alexa/Desktop/git_exercise/.git/
PS C:\Users\alexa\Desktop\git_exercise> git add .\README.md
PS C:\Users\alexa\Desktop\git_exercise> git commit -m "initial commit"
[master (root-commit) 21da833] initial commit
 1 file changed, 2 insertions(+)
 create mode 100644 README.md
PS C:\Users\alexa\Desktop\git_exercise> git status
On branch master
nothing to commit, working tree clean
PS C:\Users\alexa\Desktop\git_exercise> git branch -M main
PS C:\Users\alexa\Desktop\git_exercise> git remote add origin https://github.com/AL2002MI08/gym_git_exercises.git
PS C:\Users\alexa\Desktop\git_exercise> git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.

PS C:\Users\alexa\Desktop\git_exercise> git push --set-upstream origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 242 bytes | 242.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/AL2002MI08/gym_git_exercises.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
```