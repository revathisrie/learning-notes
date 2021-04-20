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
