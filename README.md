CIS 191 Project 3
-----------------

This is a demo site that is a simplified version of the CIS 191 website. It is
used as a testbed/training ground for Git usage and merge conflict resolution.

My git hook runs whenever I push my deploy branch from my local repo to my remote EC2 rep and does the following:
    1) copies files from the newly pushed deploy branch into a directory www. The python server will later publish the directory online. 
    2) prints  a message telling the user that the server is restarting
    3) restarts the server in case changes have been made to it.

A bare repository is a repository that doesn't yet have a working directory

The python server publishes the www directory online (www contains the files copied from the deploy branch)
