# Git Lesson

This lesson covers the basics of using git for version control.

This lesson is for the first day of the MSSE bootcamp.

To make a commit (or "verion" or "checkpoint") of your files,
follow this procedure:

1. Make changes to your project that you would like to keep.
2. When you have made your changes, tell git you are ready to create a commit by adding files to the staging area using "git add <filename>"
3. Create a checkpoint ("commit") using 'git commit -m  "message about what you did"'

## Adding Features
Features should be developed on branches.
To create and switch to a branch, usthe the comman

`git switch -c new_branch_name`

To swich to an existing branch, use

`git switch branch_name`

To list all branches, use 

`git branch`