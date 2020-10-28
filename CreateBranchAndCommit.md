1. Create Branch from the master to make changes/add feature
   git checkout -b DevBranch
2. make changes in the local repo
3. then add the changes to local git repo
   git add .
   git commit -m "the file CreateBranchAndCommit.md added to DevBranch"
   4 then add push the changes to DevBranch in Github
   git push origin DevBranch
   5 then go Git Hub and create a Merge Request
   Merge from DevBranch to Master
   6 After merge
   git pull origin master
