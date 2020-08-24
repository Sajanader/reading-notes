## version control system 
is a system save all changes and allows us to revert a file or project to a previous version, track modifications and modifying individuals, and compare changes. By utilizing a Version Control System (VCS),
mistakes with files can easily be rectified.

## Centralized Version Control; this system  allows agroup of developers to work in the same project as the team and it allows client to access that project.
there are lot of disadvantage of A Distributed Version Control systems (DVCS) like:
1. If a CVS goes down, collaborators cannot work with each other on a file or save changes and new versions. 
2. in the event of corruption of a central database’s hard disk — with the absence of backups — all work will be lost, except for any portions on local machines.
however in our programming every thing has a soulution by:
 **allowing clients to create mirrored repositories. These data backups can be easily be placed on the server to replace any lost information**
 ##git is used for manage mulipul commands and watch it to see the changes and save every version.
 * you as developer you can save your work on your local computer and work if you are offline; but you have to do upيate continuously to save work in cloud.
 ### git can do:
 
* Track changes

Every change applied to any file or directory is tracked by Git. As the gatekeeper, Git will always detect file corruption or information loss during the transfer.

* Data loss
Git is designed to reduce the possibility of irreversible file corruption, such as accidental data loss. Git makes it extremely difficult to get a snapshot of your file committed to losing it.

* States
Files in Git can exist in three main states: committed, modified, and staged.

* committed
The data is stored securely in a local database

* Modified
The file was changed but the database was not committed
![image](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)
you can run git by three ways by; 
* terminal 
*github
*gitwesite
remebre you have to install it.
### Importing
To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:
**Switch to the target project’s directory**
Example:
$ cd test (cd = change directory)
**To start tracking these repository files, perform an initial commit by typing the following8*:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”
**You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s UR**:
$ git clone https://github.com/test
## workflow happens like the picture below:
![image](https://blog.udemy.com/wp-content/uploads/2015/08/image036.png)
## The Life Cycle of File Status happen like picutre below:
![image](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

## Check File Status
$ git status

## Tracking and Staging a New File
**Single File**
git add filename
All Files

## Track all files in a repository by using the following command:
$ git add *

*After using these commands, files are tracked and staged for committing*.

## seeing information regarding changes to be committed when using the git status command:
$ git status


## Committing a File
$ git commit -m “made change x,y,z”

## Committing All Changes
$ git commit -a

## Pushing Changes
$ git push origin master

