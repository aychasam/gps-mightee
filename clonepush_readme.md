# https://dont-be-afraid-to-commit.readthedocs.io/en/latest/git/commandlinegit.html#some-basic-git-operations # Explaination of some of following command can be found in this website.

$ cd /idia/users/wanga
$ git clone https://github.com/idia-astro/gps-mightee.git # clone gps-mightee to local, get a direcoty of gps-mightee 
$ cd gps-mightee 
$ git branch -a # show all the branch
$ git checkout -b Wanga_branch master # create a new branch Wanga_branch
$ git checkout master # go back to master branch
$ git push -u origin Wanga_branch # push the new created branch into github
$ git init # To initialize in the custom branch 
$ git add file_name # To add file in the custom branch
$ git commit -m file_name # To commit file to custom branch
