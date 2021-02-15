# Project 2

## Branch-ing out

-Created a branch in my  repository called `git-guide-update` </br>

-Updated git guide.md and added the following: </br>

- Branch</br>
  - How to create a branch</br>
    A new branch is created using :  git checkout -b git-guide-update</br>
  - how to switch to a branch :        git checkout [branch name] </br>
    Here I switched back to main branch : git checkout main </br>

  - How to make changes in a branch (what happens, do you still need commits?) </br>
    Switch to that branch :     git checkout git-guide-update </br>
    Make changes :              git add . </br>
    Commit changes :            git commit -m "added new file to branch" </br>
    Push :                      git push  --set-upstream origin git-guide-update </br>


  - How to merge a branch with main / master : </br>
    Switched to main branch  using  : git checkout main </br>
    Merged git-guide-update using : git merge git-guide-update </br>
    Resolved merge conflicts in Atom.
