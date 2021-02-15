# Project 2

## branch-ing out

-Create a branch in your repository called `git-guide-update`

-Update your git guide using your project feedback (if any) and add the following:

- branch
  - how to create a branch
    a new branch is created using :  git checkout -b git-guide-update
  - how to switch to a branch :        git checkout [branch name]
    Here I switched back to main branch : git checkout main

  - how to make changes in a branch (what happens, do you still need commits?)
    Switch to that branch :     git checkout git-guide-update
    Make changes :              git add .
    Commit changes :            git commit -m "added new file to branch"
    Push :                      git push  --set-upstream origin git-guide-update

  - how to merge a branch with main / master :
