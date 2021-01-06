# collaboration_with_John_git_tutorial

This is a tutorial to use git in collaboration mode.

To start, first initiate git from you Termina:

$ git init

Something useful that you might consider to do, is to set your user name and email, if it's not set yet. You only need to do it once: 

$ git config --global user.name "Your Name"

$ git config --global user.email "Your Email"

To fork from the repository: See Edith's slides

The git clone command will take a copy of the repository and checkout a working copy for you:

$ git clone https://github.com/saraghsm/collaboration_with_John_git_tutorial

$ cd collaboration_with_John_git_tutorial

Add the main repository as a remote repository, called origin:

$ git remote add origin https://github.com/saraghsm/collaboration_with_John_git_tutorial

You can check the remote repositories with:

$ git remote -v show

To make a new branch:

$ git checkout -b new_branch_name
