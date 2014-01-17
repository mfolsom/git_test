upstream remote

An upstream remote is the term usually used when a person forks a repository and then wants to track changes on the original repository it was forked from. 

Example: I fork a repo from joe called joes_repo
I would create a remote origin to my own copye repo (joes_repo in my github account) but to pull changes from the original version I forked from (joes_repo in joe's github account), I would create a remote called upstream pointing to joe's repo on his git hub account.

git remote add upstream git@github.com:joe/joes_repo.git