# Hello-World

**Description:**

Repo for testing things on github. Do not commit important programs to this repo.

**Location:**
https://github.com/GAV-CS/Hello-World.git

Quickstart Guide:

>**Turning a folder into a repository:**
>
>`git init`
>
>**Adding repository to computer**
>
>`git clone <location>`  
>`git clone <location> <filename>` (Clones the repository into a file you name) 
>
>Adding repository to an exiting git:
>`git remote add <name for remote source> <location>` 
>
>**Tracking your changes:**
>
>`git add .` or `git add *` should be run from the root or the location the changes have been made.
>Git will find what file have been added or changed. Files can also be specified (Required if the
>file in question is specified by gitignore as not to be tracked) through `git add <file>`
>
>`git commit` adds files to the repository. They can now be pushed, pulled, or recovered (not covered in this tutorial). 
>
>**Managing a repository using remote:**
>
>_Local:_  
>`git pull` (Defaults to pulling origin master)  
>`git pull` <name for remote source> <branch> (pulls from the location defined)  
>
>_Remote:_  
>`git push` (Pushes to the remote "origin master")  
>`git push` <name for remote source> <branch>  (Pushes to the  location defined)
>
>**gitignore.txt**  
>In repositories, there is often a file named gitignore.txt, which lists rules for which files git should not track. 
>Use this file to exclude any files that contain sensitive information, like passwords, or for backup files made by word processors.
