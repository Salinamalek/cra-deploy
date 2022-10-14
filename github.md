## main

    \_______________/
        branch to do some work

How do I create a branch?
checkout tells us to go to a different place
-b is saying create a new branch
git checkout -b <name of your branch>

to combine add and commit use

git commit -am "message"

to see all branches

git branch
hit Q when you are done viewing the branches

To push to a branch

git push origin <branch name>

git checkout <branch name> without the b allows you to look at a branch check it out

git checkout -
takes you to the last branch you were at

git pull origin main
do this after you merge on github and before you add anything else to your main branch
