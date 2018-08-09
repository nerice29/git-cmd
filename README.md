
git-cmd

# basics command for working with git cms

$ git init 

  # Init new git repository , tell we want to use git in the current repository

$ git status

  # check all about your work status such as commits,current branch and all modifications

$ git branch 

  # return all work branch and specified the current branch

$ git branch <branch name> 

  # create new branch

$ git checkout -b [name_of_your_new_branch]

  # Create the branch on your local machine and switch in this branch

$ git checkout [name_of_your_new_branch]

  # Change working branch

$ git add [file_name] 

  # Adds the [file_name] in the local repository and stages this for commit | validaton

$ git reset HEAD [file_name]

  # unstage a file

$ git add . 

  # Adds the files in the local repository and stages them for commit

$ git commit -m"[your_message_here]"

  # commit | validate your change in your current work branch

$ git remote add [your_remote_url] 

  # add the github remote project url 

$ git remote -v

  # Verifies the new remote URL

$ git push origin [branch_name]

  # push your work to the remote specified branch to github
