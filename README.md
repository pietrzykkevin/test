# test
1. add repository on git
2.  - First i cloned this repository using comand:
	git clone https://github.com/pietrzykkevin/test mytest
    - changed directory
	cd  mytest
    - added branch and changed to it
	git branch addtoRM
	git checkout addtoRM
    - edit README.md

  my following acts will be:
    - add to staging area Readme.md
	git add README.md
    - commit changes
	git commit -m "instructions I used"
    - go to master a merge
	git checkout master
	git merge addtoRM
    - push file to origin
	git push origin master
