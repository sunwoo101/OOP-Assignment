# Git Manual
# 1. Write instructions on installing git on a windows system.

## Minimum System Requirements
- Windows 7 and higher
- 1GB RAM or more
- 50MB disk space or more

## Installation Instructions
1. Download the Windows installer for Git
2. Install Git using the installer
3. Run git to check if it is working properly
4. If you have any issues installing Git you can ask a co worker or a senior engineer for help

# 2. Do research on some principles/techniques of industry standard best practices creating and working with repositories and branches in Git. 
## Repositories
Make a separate commit for each bug and feature so it's easy to rollback to a previous version if there are any issues

## Branches
Make separate branches for development, staging and the main branch. Make sure a commit and merge is successful before merging into main

# 3. List the steps in a Git workflow that the team should follow when working on projects.
1. When developing, only make changes to the development branch
2. Don't merge the development branch into main. Merge into the staging branch first to make sure there are no merge conflicts
3. If the development branch merge into staging branch is successful you can merge the staging branch into the main branch