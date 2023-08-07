Hello , this text is written through the terminal app
This is the first change


------------------------------------------------------
this change was made in the feature branch.
To understand the working of pull request



--------------------------------------------------------
this change is now done in Local:master .
Let's try to understand the working of the pull requests.
-------------------------------------------------------




checking if changes in master branch require pull requests or are directly commited?
YES! Local:master -- Remote:master , changes are reflected directly.

But , Other Remote:master to Remote:feature - requires pull requests.


---------------------------------------------------------------------------
IMPORTANT
----------------------------------------------------------------------------
git pull -  is when origin is involved- for updating the branches

git merge - is when changes on Local:branch-1 has to be reflected in Local:branch-2 
ex:  git checkout dev-branch

on branch -dev-branch

For changes in dev-branch to be reflected in Local:master

git checkout master
git merge dev-branch {whatever is there in dev-branch , bring it to Local:master}





