## Using the command for add and committing in the same command
    -> git commit -a -m "message"
        => not giving desired results.

## Doing global configurations
    -> git config --global user.name 'name'
    -> git config --global user.email 'email'
    -> git config --global init.default branch main
    -> git config --global init.defaultBranch main

## Creating a new branch
    -> git branch new-branch-name
        => creates a new branch but does not immediately check into the branch
    -> git checkout -b new-branch-name
        => creates a new branch and checks into the created branch
    -> git switch -c new-branch-name
        => not working :: no longer a git command

