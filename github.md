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

to locally delete branch use
git branch -d <name of branch>
if you get message that it won't dlete use
git branch -D <name of branch>

I am creating a Contact component. I want to then push it to Github without my netlify updating.
1 - create a local branch
2 - create components directory
3 - create contact.js
4 - git status look at updates
5 - git add .
6 - git commit -m <message in quotes>
7 - add component to the app.js
8 - npm start to see if it works
9 - git status check everything is staged
10 - git add
11 - git commit
12 - push branch to github
13 - check github
14 - compare and pull request click
15 - make notes look at changes
16 - click merge
17 - wait for netlify to do its checks as well
18 - click confirm merge
19 - delete branch on github
20 - go back to local porject
21 - cd to main
22 - delete branch from main
23 - pull info from github to local git pull origin main
24 - check deployment site
