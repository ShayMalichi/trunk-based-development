# Trunk Based Development

Trunk based development is a git workflow, such that the development is mostly on one branch (usually main). 
small changes or bug fixes are done on a separate branch and merged to main as soon as possible to avoid merge conflicts. 

|Trunk Based Development |alternatives                         
|------------------|-------------------|
|one branch that small changes integrated to that branch frequently | each development groups have their own branch (could be a long branch) on that branch the group keeps expanding the main project    |         
|easy to review small changes, easy to maintain the main working branch            | merging a long branch to main could lead to lots of                  	                      conflicts and hard to review small changes.  |
|less chance of new changes break the main project build. |could be hard to integrate a long branch to main branch

- those benefits make the main branch always production ready. 

#### workflow
* the core project is on the trunk branch 
* we want to fix a bug or work on a small change 
* open another branch 
* fix the bug or finish the small feature update 
* pull request for review on small change or bug fix
* merge it into main and delete the branch. (quickly) 
* trunk branch is clean, organized and production ready all the time.  


