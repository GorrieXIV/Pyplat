# Pyplat

## Overview
Pyplat is an in-house, pygame-based, 2D platformer with a linearly progressing storyline.


## Instructions for Contributing
### Setting Up
  * Fork this repository by clicking the "Fork" button in the top right-hand corner.
  * Clone your fork: `git clone https://github.com/<YOUR_GITHUB_USERNAME>/Pyplat.git`
  * Setup upstream repo as remote: `git remote add upstream https://github.com/ArkellTechInc/Pyplat.git`

### Adding Features/Bug Fixes
  * When you begin development on a new feature, first create a branch on your fork:
    * Navigate to your local fork: `cd <path_to_repo>/Pyplat`
    * Create a new branch for development: `git checkout -b <name_for_new_branch>`
    * Push your local branch to remote: `git push -u origin <name_for_new_branch>`
  * Post in the 'dev-notifications' slack channel to alert people of where you plan to work
  * Make your changes
  * Remember to add useful comments

### Contributing Your Work
  * Commit & push your edits to the remote branch:
    * Track changes: `git add <file1> <file2> ...`
    * Commit changes: `git commit -m "INSERT A USEFUL COMMIT MESSAGE HERE!"`
    * Push changes to your remote branch: `git push origin <name_for_new_branch>`
  * Open a pull request on the upstream repo:
    * On Github, navigate to GorrieXIV/Pyplat and click the "New pull request" button
    * Specify the branch from your fork that that contains the work you wish to add
    * Give an apt name and description for the work you are contributing
    * Submit the pull request for review by another developer
    * Once reviewed (and after edits, if necessary,) the pull request will be merged into master

### Getting updates from the upstream repo
  * `git checkout master`
  * `git fetch upstream`
  * `git merge upstream/master master`
    * Consider pushing those updates to your fork online: `git push`

## Team
  * Rob Gorrie - <role>
  * Kurtis Trainor - <role>
  * Jack Caunter - <role>
