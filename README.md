# Basic Commands
These are the basic commands that every developer should follow while deplying any changes into GitHub repository.

#### Step 1. First go to your branch.
     git checkout mahesh

#### Step 2. Pull all the previous changes.
     git pull 
     or 
     git pull origin master

#### Step 3. Check your all the files in which you have made some changes.
     git status

#### Step 4. Add your changes into stagging.
     git add --a

#### Step 5. Save your changes to the local repository.
     git commit -m "Added list board function"

#### Step 6. Push your changes to your branch.
     git push --set-upstream-to origin mahesh
     or
     git push origin mahesh
     or 
     git push

#### Step 7. Checkout to master from your branch.
     git checkout master

#### Step 8. To make your local repository upto date.
     git pull

#### Step 9. Now merge your branch into master.
     git merge mahesh

#### Step 10. At last push your changes to remote repository.
     git push
