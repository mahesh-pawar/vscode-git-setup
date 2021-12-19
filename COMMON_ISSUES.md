# Common Issue
These are some common issue that we faced every now and then while working on Git.

## Your branch and ‘origin/master’ have diverged

#### Issue -

Your branch and 'origin/master' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   application/controllers/builder_login.php

#### Solution -

`git reset --hard origin/master`  
