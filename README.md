1# body-building-app

This is a devOps project used to show the workflow of git.
As a student we have been asked to perform this tasks which is used to simulate how different team members 
submit project code using git branch. i learnt how to create branch, switch between branch, pull changes in a branch,
push a branch

To create a branch use: 
> git checkout -b branch-name-you-want

the above code create the branch and automatically switch into that branch.

To check which branch you are on use 
> git branch 

This will show you all the branch in your system and the one you are on will be green and prefixed with the symbol *

To switch to another branch use 
> git checkout branch-name

To push changes in a branch to the remote repository use 
> git push origin branch-name

To pull it back, that is to get the changes done on that branch locally you can use 

> git pull origin branch-name

this will pull the branch changes into any branch you are currently on and make the necessary changes so you are up to date.

below are pictures of how what i have explained above was used by me.

![workflow1](./images/git-workflow-1.png)

![workflow2](./images/git-workflow-2.png)

![workflow3](./images/git-workflow-3.png)

![workflow4](./images/git-workflow-4.png)

here are the merging i did

![merge update-navigation to add contact](./images/update-navigation-merge.png)

![merge update-navigation to main](./images/merge-nav-to-main.png)


WORKING OF PULL REQUEST TASK.

Tom pulls in changes in the main branch using 
> git pull origin main

Tom pulls in changes in the main branch using 
> git pull origin main

There was a conflict which was resolved as shown in the image follow  the one below.
![pull in changes](./images/Tom-conflict-pulling-main.png)

resolving the conflict for tom
![tom resolve conflict](./images/Tom-accept-change.png)

after accepting which changes to keep, Tom pushed the changes to it branch using 
>git push origin update-navigation

Tom push changes to the update-navigation branch

![Tom push](./images/tom-push-changes-to-it-branch.png)

Tom made a pull request with it new changes.

![Tom pull request](./images/Tom-pull-request.png)

Tom describes the reason for the pull request

![description of pr](./images/Tom-description.png)

Tom pull request was accepted and merge by team member.

![pr merged](./images/Tom-requesting%20merge.png)

Tom pull request merge successful message

![Tom merge successfull](./images/Tom-pull-request-successful-message.png)

----------------------------------------------------------

==========================================================

==========================================================
![pull in changes](./images/jerry-pulls-changes.png)

jerry push changes to the add-contact branch

![jerry push](./images/jerry-push-changes.png)

jerry made a pull request with it new changes.

![jerry pull request](./images/pull-request-for-jerry.png)

jerry describes the reason for the pull request

![description of pr](./images/jerry-pr-description.png)

jerry pull request was accepted and merge by team member.

![pr merged](./images/merging-pr-for-jerry.png)

jerry pull request merge successful message

![merge successfull](./images/merge-message-of-jerry-pr.png)

