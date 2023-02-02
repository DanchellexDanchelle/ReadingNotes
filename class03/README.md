# Read03
## Different types of Version Control

Version Control is a way to revisit changes you made to a file/files
    * something like a googledoc save points

Centralized version Control (CVC)- one server that stores changes and files different versions that can be accessed by different "client"

Distributed Version Control(DVC) is basically a backup feature for CVC 

## What is a Git?

Git is a DVC that store data using **snapshots**
*each save is a snapshot. 
*if nothing is saved it refrences the last save

Git mostly rely on local operations which allows the information to accessed even offline
Git is set up so that there is litle to no data loss

Git files have three main states
1. Committed
     * data is securely store in a local database
2. Modified
     * file has been changed but not committed to the database
3. Staged
     * Flagged a file's changed version to be committed in the next snapshot
     
  
## Initial Customiztion 
 Once git has been installed you should customization setting which you only have to be done once but can be changed
 The tool is call "git config" to change variables
 Set Name & email 
 
 
 ## the life cycle of file status 
 1. after you make a change to a file git flags it as modified
 2. you stage the modified file
 3. then you commit 
 ![image](https://user-images.githubusercontent.com/123973263/216150358-0b1fa89c-e659-4258-9dc4-0111012dc946.png)

  ## Download Git 
     Git can Be downloaded three different ways
     1. Install as a Package
     2. Install via another installer
     3. Download and compile the source code
     
  Install w/ Ubuntu : $ sudo apt-get install git
  
  ## once downloaded
  
1. Check file status
   * git status
2. Tracking and Staging a new File
   * Single files- git add filename
   * All files- $ git add 
3. Commit files and changes
   * git commit -m "made change x,y,z"
   * $ git commit -a
4. Pushing changes
   * $ git push origin master
5. Stashing Changes
   * git stash 
