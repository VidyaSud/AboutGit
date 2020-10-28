1) Create project in local machine
2) Go to command line and execute  git init --> this will initialize the empty Git repository in the current project/.git/
3) Go to current project root folder and create ".gitignore" file then add below line.
node_modules
.DS_Store // only for mac
4) git add .
5) git commit -m "Initial commit"
6) Now we have upto date git Repository on local machine.

Create Repository on Git Hub

1) Go to git hub and create a Repository in the gitHub called "ticketing"
2) Map this Git Repo to the Repo which created in Local machine as above.
3) Copy the link of the Git Repo and go to command line

Git remote add origin <copied url of the git Repo>
4) Git push origin master
