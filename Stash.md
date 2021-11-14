# Stash

The git stash command takes your uncommitted changes (both staged and unstaged), saves them away for later use, and then reverts them from your working copy.

**To save uncommitted changes** - 
> git stash save "add style to our site".

**Lists all the stashes** -
> git stash list

**Gets latest stash from stash list** -
> git stash pop

**Gets specific stash by index** -
> git stash pop stash@{2}

**Removes specific stash from list** -
> git stash drop stash@{1}

**Removes all the stashes from list** -
> git stash clear
