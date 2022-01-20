# create GIT first time
> git init
> git add "index.html"
> git commit -m "first commit"
> git remote add origin https://github.com/neocaptain/git-example-project.git
> git push -u origin master

# update changes to GIT
> git status
> git add .
> git status
> git commit -m "added 2nd paragraph to index.html. add 2nd page to project"
> git status
> git push
> git status

# restore local file not applying add commd from GIT (content restore )
> git restore index.html

# restore local file from GIT after adding command( just status retore )
> git restore --staged index.html

# restore local file from GIT with previous checkout version ( content restore )
> git log
> git log --oneline

# create GIT branch
> git branch --list
> git branch NodeJS_example
> git checkout -b MyNewBranch

# delete GIT branch
> git branch -D MyNewBranch

# change GIT branch
> git checkout NodeJS_example
> git branch -m NodeJS_example NodeJS_ex

