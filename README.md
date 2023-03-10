# Project 1 repo:
### University project:
Project was about Git and GitHub and demonstrate your git skills.
Mark I recieved on this project was: 89%

## Quick overview:
This repository is used to give an overview of the projects to be done in this module. It will also be used as a guide for planning purposes and how the rest of the projects will be structured. The branching strategy that will be used in each project is also discussed within this repository. I also discuss how the .gitignore file will be used and how I will deal with sensitive information within each project. This repository will be used throughout the semester to keep track of progress that is made with each project through the kanban project that is linked to this repository.

## Stucture of projects:
Projects will each have their own repository as this will be easier to keep track of each project within their own repository. If I require work from an earlier project, forks will be used to fork the earlier repository with the new one.

#### Repository overview:
- Project 1 repository (Overview + Scrum & Setup). This repository
- Project 2 repository (API development). [CMPG323-Project-2-31609988](https://github.com/dennisvantonder/CMPG-323-Project-2-31609988)
- Project 3 repository (Standards & Patterns, Web app). [CMPG323-Project-3-31609988](https://github.com/dennisvantonder/CMPG323-Project-3-31609988)
- Project 4 repository (Testing & RPA). [CMPG323-Project-4-31609988](https://github.com/dennisvantonder/CMPG323-Project-4-31609988)
- Project 5 repository (Power BI and reporting).

#### Project overview:
Only one Kanban project will be created. This project is called CMPG 323 Planning, and this project will be linked to every repository that will be created through the semester. Here is a diagram to explain how the project will be integrated with each repository:

![Diagram](https://github.com/dennisvantonder/CMPG-323-Overview-31609988/blob/main/diagram.drawio.png)

## Branching strategy:
#### The branching strategy I will use for each repository is as follows:
1. There will be a main or master branch that will be used as the backup or stable version.
2. There will be a develop branch where new features will be created.
3. Features will be created on their own separete branch and will be merged with the develop branch once implemented.
4. Bug fixes/hot fixes will also be created on their own branch and will be merged with the develop branch.
5. After each successfull feature or fix is added to the develop branch and the current version of the develop branch is stable, it will be merged with the main branch to be kept as the latest backup.

![Branching stategy](https://github.com/dennisvantonder/CMPG-323-Overview-31609988/blob/main/branching_strat.drawio.png)

## The use of .gitignore files:
.gitignore will be used in each project to list files that should be ignored when commiting changes, these files will include files that contain sensitive information or credentials, system files, log files and files that I want git to ignore.

## Storage of credentials and sensitive information:
I will be using git-secret to store credentials and sensitive information. git-sercret is a bash tool that is used to encrypt files in a repository. git-secret uses gpg to encrypt and decrypt files, a public key is used to encrypt files and a personal private key that is given to authorised users is used to decrypt files. The tell command is used to give users their own key and to give them access to the secret files. I will be implementing git-secret on a project's repo to save passwords, API keys and other sensitive information. These files will be encrypted and will not be accessible to anyone, except for people I give access to.

## Burndown chart:
This Burndown chart is created in excel and will be continuously updated throuhout the semester.

![Burndown chart](https://github.com/dennisvantonder/CMPG-323-Overview-31609988/blob/main/Burndown%20Chart.png)

## Training completed:

#### Badges of training completed:
- [Introduction to git](https://docs.microsoft.com/en-us/learn/achievements/learn.student-evangelism.introduction-to-git.badge?username=DennisVanTonder-7832)
- [How to create and modify a git project](https://docs.microsoft.com/en-us/learn/achievements/learn.student-evangelism.create-git-project.badge?username=DennisVanTonder-7832)
- [Collaborate with Git](https://docs.microsoft.com/en-us/learn/achievements/learn.student-evangelism.collaborate-with-git.badge?username=DennisVanTonder-7832)
- [Edit code through branching and merging in Git](https://docs.microsoft.com/en-us/learn/achievements/learn.student-evangelism.branch-merge-git.badge?username=DennisVanTonder-7832)
- [Describe cloud computing](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-cloud-computing.badge?username=DennisVanTonder-7832)
- [Describe benefits of using cloud computing](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-benefits-of-using-cloud-services.badge?username=DennisVanTonder-7832)
- [Describe cloud service types](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-cloud-service-types.badge?username=DennisVanTonder-7832)
- [Describe the core achitectural components of Azure](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-core-architectural-components-of-azure.badge?username=DennisVanTonder-7832)
- [Describe Azure compute and networking service](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-azure-compute-networking-services.badge?username=DennisVanTonder-7832)
- [Describe Azure storage services](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-azure-storage-services.badge?username=DennisVanTonder-7832)
- [Describe Azure identiy, access and security](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-azure-identity-access-security.badge?username=DennisVanTonder-7832)
- [Describe cost management in Azure](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-cost-management-azure.badge?username=DennisVanTonder-7832)
- [Describe features and tools in Azure](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-features-tools-azure-for-governance-compliance.badge?username=DennisVanTonder-7832)
- [Describe features and tools for managing and deplying a resource](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-features-tools-for-managing-deploying-azure-resources.badge?username=DennisVanTonder-7832)
- [Describe monitoring tools in Azure](https://docs.microsoft.com/en-us/learn/achievements/learn.wwl.describe-monitoring-tools-azure.badge?username=DennisVanTonder-7832)
- [Build a web API using ASP.NET](https://docs.microsoft.com/en-us/learn/achievements/learn.build-web-api-net-core.badge?username=DennisVanTonder-7832)
- [Write your first c# code](https://learn.microsoft.com/en-us/training/achievements/learn.languages.csharp-write-first.badge?username=DennisVanTonder-7832)
- [Build a simple website using HTML, CSS, and JavaScript](https://learn.microsoft.com/en-us/training/achievements/learn-windows.introduction-to-web-development.badge?username=DennisVanTonder-7832)
- [Learn the basics of web accessibility](https://learn.microsoft.com/en-us/training/achievements/learn.student-evangelism.web-development-101.accessibility.badge?username=DennisVanTonder-7832)
- [Create a web UI with ASP.NET Core](https://learn.microsoft.com/en-us/training/achievements/learn.create-razor-pages-aspnet-core.badge?username=DennisVanTonder-7832)
- [Publish a web app to Azure with Visual Studio](https://learn.microsoft.com/en-us/training/achievements/learn.publish-azure-web-app-with-visual-studio.badge?username=DennisVanTonder-7832)
- [Secure a .NET web app with the ASP.NET Core Identity framework](https://learn.microsoft.com/en-us/training/achievements/learn.secure-aspnet-core-identity.badge?username=DennisVanTonder-7832)
