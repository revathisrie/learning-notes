## Git

Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

## Setting up a Repository
**Importing**: 
  * Switch to the target project’s directory 
    * $ cd test
  * Use the git init command
     *   $ git init
  * To start tracking these repository files, perform an initial commit by typing the following.
       *   $ git add *.c
       *   $ git add LICENSE
       *   $ git commit -m “any message here”

**Cloning:**
You can also create a copy of an existing Git repository from a particular server by using the clone command with a repository’s URL:
 *  $ git clone https://github.com/test
To clone a repository into a directory with another name of your choosing, use the following command format:
 *  $ git clone https://github.com/test mydirectory
The command above makes a copy of the target repository in a directory named “mydirectory.”

**Local Repository Structure:**
It has 3 components:
 * Working Directory: The actual files reside here.
 * Index: The area used for staging
 * Head: Points to the most recent commit

## ACP Process
* $ git add filename
* $ git commit -m “made change x,y,z”
* $ git push origin master

