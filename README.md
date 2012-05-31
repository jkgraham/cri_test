critest
========

Testing of git merges:

1. Setup test repo with a couple of files/foldes
1. Create a 'small-fix' branch
1. Create a 'big-feature' branch
1. To the 'small-fix' branch: 
	1. Make one or two small edits to a couple files
	1. Commit to branch and push to origin
	1. Merge into master
1. To the 'big-feature' branch:
	1. Make a change in one of the above changed files, but not in the same lines
	1. Commit to branch and push to origin
	1. Merge master into branch
	1. Merge branch into master
1. See if 'small-fix' changes are still in master
