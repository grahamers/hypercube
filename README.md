# hypercube
Not just another repo

This change was made on hithub, branch testing

0. show all branches that exist

	% git ls-remote

1. master branch and test branch.

	% git remote show origin

2. show what branch I'm on

	% git status

3. show how many commits I'm behind on local branch, you must do fetch first.
	
	% git fetch 
	% git status -sb

	## master...origin/master [behind 1]


4. show how many commits I'm behind master before I try to merge

	% git log ...<OTHER BRANCH NAME> - will show you commits made on other branch
	% git diff ...<OTHER BRANCH NAME> - will show you the diffs

5. will my commit/push require a merge

6. how to simulate a conflict

7. how to resolve a conflict with command line/vi

8. Show all commits on a file.
	% git log --follow <FILENAME>

