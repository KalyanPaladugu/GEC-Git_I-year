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

+ To initialize git dependencies in for your repository use `git init`

+ Mainly in git we have 3 areas
    - Untracked area ()
    - Stagging area
    - Commit area

+ To check the files are tracked or untracked use `git status`
+ To add file to stagging area use command `git add filename`
+ To move all files from unstage to stagging area use command `git add .` or ` git add --all`
+ To untrack specific file from stagging area use command `git rm --cached filename`
+ To coomit your data to the git use `git coomit -m "commit message"`