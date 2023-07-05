# Projects Specifications

This repository contains the projects specifications for the trainees. Each trainee has a folder where he or she can find the specifications for the assigned projects.

## Instructions

To work on a project, follow these steps:

- Create a new repository on GitHub with the name of the project.
- Clone the repository to your local machine.
- Initialize git flow by running git flow init and following the prompts.
- Protect the master branch on GitHub by going to Settings > Branches > Add rule and selecting master as the branch name pattern. Check the options "Require pull request reviews before merging" and "Include administrators".
- Create a new feature branch for each task or functionality of the project by running git flow feature start <feature-name>.
- Work on the feature branch and commit your changes regularly.
- When the feature is done, push the branch to GitHub and create a pull request to merge it to the develop branch. Request a review from your mentor or another trainee.
- After the pull request is approved and merged, delete the feature branch locally and remotely.
- Repeat steps 5 to 8 for each feature until the project is complete.
- When the project is ready for release, create a release branch by running git flow release start <version-number>.
- Bump the version number in the project files and commit the changes.
- Push the release branch to GitHub and create a pull request to merge it to the master branch. Request a review from your mentor or another trainee.
- After the pull request is approved and merged, tag the master branch with the version number by running git tag <version-number>.
- Push the tag to GitHub by running git push origin <version-number>.
- Merge the master branch to the develop branch by running git checkout develop and git merge master.
- Push the develop branch to GitHub by running git push origin develop.
- Delete the release branch locally and remotely.
- Congratulations, you have completed the project! 🎉
