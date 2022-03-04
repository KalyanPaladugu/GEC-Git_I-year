# Source Code Managment Using Git & Github

### Version Control System (VCS)

+ Version Control is a system that track the history of a file or files or project
+ Types of VCS
    - Local Version Control System
    - Distributed VCS (Offline)
        - Git,Mercurial
    - Central(Remote) VCS (Online)
        - Github,Apache Subversion, Bitbucket

#### Uses of Git & Github

 - While doing Global certifications like Android Developer or Frontend Nanodegree  Udacity,Courseera and Google they will prefer Git & Github
 - We can track the history of files in the project
 - While working on a project to collaborate with team members we can use Git & Github

- [Download Git](https://git-scm.com/download/)

+ Git bash

+ Git GUI

###### Commnads in Git Bash

+ To move from one folder to another we have to use `cd foldername` 
+ cd --> change directory
+ To comeback previous folder use `cd ..`
+ To create any directory use `mkdir foldername`
+ To see list of files in a directory use `ls`
+ To see hidden files in a directory use `ls -a`
+ To create file use `touch filename`
+ Git bash editors
    - vim filename
    - nano filename
        - To quit from nano editor use `ctrl+x`
        - select `y` for save the code
        - click on Enter

+ To access data from specific file use `cat filename`

#### Git commands

+ To initialize git dependencies in for your repository use `git init` (Default it will create `master` branch)

+ Mainly in git we have 3 areas
    - Untracked area ()
    - Stagging area
    - Commit area

+ To check the files are tracked or untracked use `git status`
+ To add file to stagging area use command `git add filename`
+ To move all files from unstage to stagging area use command `git add .` or ` git add --all`
+ To untrack specific file from stagging area use command `git rm --cached filename`
+ To coomit your data to the git use `git commit -m "commit message"`


+ To push the content from git github we have to configure use logins(email and username)

+ Add the username to git use `git config --global user.name "githubusername"`
    - Check whether the user is added or not by `git config user.name`
+ Add the user email to git use `git config --global user.email "githubemail"`
    - Check whether the user is added or not by `git config user.email`

+ Try to commit once again
+ Create one repository in github
+ Copy remote command in the github ex: `git remote add origin https://github.com/KalyanPaladugu/demo.git`
+ Check the remote whether it is added or not by `git remote`
+ To remove specific remote use `git remote remove remotename`

+ To push the content from git to github use `git push -u origin master`

+ To unset git user.email use the command `git config --global --unset user.email emaild`

+ + To unset git user.name use the command `git config --global --unset user.name username`


+ To check the number of commits use `git log`
+ To check the commit message with first 7 characters of SHA key use `git log --oneline`
+ To navigate from one commit message to another or from one branch to another use `git checkout xxxxxxx` 
