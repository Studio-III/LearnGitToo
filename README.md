# LearningGit
We'll use this to help us learn to use Git

Not sure how that's working out at this point.

If you're trying to push something onto the git repository and it thinks that your version is too far behind the repository's master, do the following:
	git pull https://github.com/Studio-III/LearnGitToo

then it will most likely have conflicts. open the file that has conflicts in a text editor and take out the extra text that it put in. Some of the text that it might put in is:
	>>>>>>>>>>
	<<<<<<<<<<
	HEADetcetcetc.
	
Save it. Then do the following and you're done!:
	git add filename.filetype (i.e. index.html)
	git commit -m "I changed such and such"
	git remote add origin https://github.com/Studio-III/LearnGitToo
	git push origin branchName (i.e. master, or a branch that you made)