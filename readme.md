# Test repo for people to practice committing PR's to github

## Step 1

Clone the repository

`git clone https://github.com/trevorcode/GitPracticeSite.git`

and change directory into the project.

`cd ./GitPracticeSite/`

## Step 2

Create a new branch

`git checkout -b "MyNewBranch"`

## Step 3

Make your code changes

You can periodically use `git status` to see what files have been changed.

## Step 4

Add files to be staged to commit

`git add <filename or directory>`

I tend to just do `git add .` as it will add all the files I've changed in the folder.

You can do `git status` again to check and see if they've been added correctly.

## Step 5

Commit to your local repository/branch

`git commit -m "Here is my commit message"`

## Step 6

Push branch

`git push --set-upstream origin <Your Branch Name>`

For example

`git push --set-upstream origin MyNewBranch`

## Step 7

Go to your branch on github and open a new Pull Request
