# html_css_bootstrap_project

this is not the complete project it is somewhere in one of the other repositories.

how to upload a project file folder to git
1. go to the folder you have saved all your files in make sure index.html is in it making it the root. right click start git bash here
2. command 1 git init
3. git status
4. git add .
5. git status to check all the files are 
6. git commit -m "comment"
7. git remote add origin https://github.com/harshmishra2/html_css_bootstrap_project.git
8. git push -u origin master

if in case there is error : fatal: remote origin already exists.
refer to https://stackoverflow.com/questions/10904339/github-fatal-remote-origin-already-exists .
like in the case of this project i named remote html_css_bootstrap_project and moved on.

i tried pushing directly into branches but was unable now I have spent over 5 hours trying to do so and wasted somewhere about tens of hours dues to them, i'll just keep on pushing into the master branch and use history of files as reference now.

git log --oneline
git checkout <000cfcf no. like this corresponding to commit> index.html //this thing reverts index.hmtl back to the no. version of commit
git checkout --index.html // restores everything

git clone <url of repo> //to clone online repo from git on a new foreign computer
  
