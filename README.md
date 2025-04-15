# gitforteams
How to
Describe the work your team does
+ The (Devs - Lead Dev, Scrum master, or Operators) will initialize a Master branch
+ From the Master branch, the (Devs- Lead Dev, Scrum master, or Operators) creates a Develop branch
+ From the Developer branch, 3 developers will create a new branch to create new one or more Feature Branch
+ After the Developer has done the feature in the Feature branch, they create a pull request for Reviewers (Devs - Lead Dev or Scrum master)
+ Reviewers (Devs - Lead Dev or Scrum master) will check and merge the Feature Branch into the Developer branch, and merge the Developer branch into the Release branch
+ Reviewers (Devs - Lead Dev or Scrum master) will merge the Release branch into the Master branch (at this time, the Master branch will be tagged for the new version)
+ 2 operators will use the Master branch (with the new version tagged) to deploy for users
+ If there are any issues in the Master branch, developers will create the Hotfix branch to fix the problems and let Reviewers (Devs - Lead Dev or Scrum master) review and merge it into the Master branch (The master branch will update the new tag version for hotfix) and merge this issue or cherry-pick the commit into Developer branch
+ The Project manager will check the timeline for the progress the Devs team is working, and review the repo history of commits, issues, and releases without commit/push permission


Diagram my branching strategy

![GitChart drawio (1)](https://github.com/user-attachments/assets/04f38be8-1d45-4c7e-84b7-d0e6c637687e)


Defend what gets stored in the repo.

+ Create 3 rules to protect master, release, and develop branches and 1 rule for tag

![Screenshot_39](https://github.com/user-attachments/assets/ce0f4c4e-6e3c-4d19-aacf-00fcdc089d37)

+ Rule for develop

![Screenshot_40](https://github.com/user-attachments/assets/7ac600c0-be22-497c-8b74-c18786e978d8) 


+ Rule for release

![Screenshot_42](https://github.com/user-attachments/assets/b3c0216f-11a6-4034-96fe-933122528f73)

+ Rule for master

![Screenshot_41](https://github.com/user-attachments/assets/b78d365d-0173-4896-90e4-3b3e8fa91ed9)

+ Rule for tag

![Screenshot_43](https://github.com/user-attachments/assets/35398a1d-ceff-4b62-9ebe-39f89ec73ca3)


