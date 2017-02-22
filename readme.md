<h1>Git Practice</h1>

<h2>Github - Where ALL the code lives.</h2>        
*Create a new repository on Github.* 
Clone the repository.  `git clone https://github.com/pchinjr/gitpractice.git` - will copy that repo into a folder with the same repo name  
navigate into project folder `cd gitpractice/`
create file  `touch a.txt`
add file to staging  `git add .` adds all the files you have created to a staging area  
commit file to staging  `git commit -m "commit message"` commits that file to a staging area with a commit message  
push file to repo  `git push origin master` pushes those commits to the remote repository on github

*Branches*  
make a branch `git checkout -b develop`  
+make changes  
+add changes  
+commit changes  
+push changes  

*Pull Request*    
Pull requests are specific to github, from the feature branch it asks for a merge into another branch. In this case, we are accepting changes from `develop` into `master`. If the merge looks good, you can accept it.  

*Make a new feature branch*  
create a branch  
review branch and accept into `develop`
once merged into develop, delete feature branch. 

*Other git tools*  
Rebase - squash commits and rewrite git history  
Bisect - go through each commit to find bugs  

Work on the latest `develop` and patch that one first, changes should flow up from fixes to features to develop to master.  
Version control is not a solution to team communication. 