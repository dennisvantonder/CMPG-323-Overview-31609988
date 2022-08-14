# Project 1 repo:

## Quick overview:
This repository is used to give an overview of the projects to be done in this module. It will also be used as a guide for planning purposes and how the rest of the projects will be structured as well as the branching strategy that will be used in each project. I also discuss how the igitignore file will be used and how I will deal with sensitive information within each project.

## Stucture of projects:
Projects will each have their own repository as this will be easier to keep track of each project within their own repository as well as linking repositories is always an option.

#### Repository overview:
- Project 1 repository (Overview + Agile & Scrum).
- Project 2 repository (API development).
- Project 3 repository (Standards & Patterns).
- Project 4 repository (Testing & RPA).
- Project 5 repository (Reporting & Monitoring).

## Branching strategy:
#### The branching strategy I will use for each project is as follows:
1. There will be a main or master branch that will be used as the backup or stable version.
2. There will be a develop branch where new features will be created.
3. Features will be created on their own separete branch and will be merged with the develop branch once implemented.
4. Bug fixes/hot fixes will also be created on their own branch and will be merged with the develop branch.
5. After each successfull feature or fix is added to the develop branch and the current version of the develop branch is stable, it will be merged with the main branch to be kept as the latest backup.

![Branching stategy](https://github.com/dennisvantonder/CMPG-323-Overview-31609988/blob/main/branching_strat.drawio.png)

## The use of .gitignore files:
.gitignore will be used in each project to list files that should be ignored when commiting changes, these files will include files that contain sensitive information or credentials, system files, log files and files that I want git to ignore.

## Storage of credentials and sensitive information:
