# gitforteams
How to
Describe the work your team does
+ The project manager will initialize a Master branch
+ From the Master branch, the project manager creates a Develop branch
+ From the Developer branch, 3 developers will create a new branch to create new one or more Feature Branch
+ After the Developer has done the feature in the Feature branch, they create a pull request for the Reviewer
+ The Reviewer will check and merge the Feature Branch into the Developer branch, and merge the Developer branch into the Release branch
+ The Reviewer will merge the Release branch into the Master branch (at this time, the Master branch will be tagged for the new version)
+ 2 operators will use the Master branch (with the new version tagged) to deploy for users
+ If there are any issues in the Master branch, developers will create the Hotfix branch to fix the problems and let the Reviewer review and merge it into the Master branch (The master branch will update the new tag version for hotfix) and merge this issue or cherry-pick the commit into Developer branch


Diagram my branching strategy

![GitChart drawio (1)](https://github.com/user-attachments/assets/04f38be8-1d45-4c7e-84b7-d0e6c637687e)


