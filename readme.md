# Purpose
## This project aims to document the following:
- How to use Github Desktop to commit code
- How to use Github to manage versioning
- How to use jsDeliver to deploy code into live projects
- How to collaborate using Issues and Branches

### Tools
- Visual Studio Code
- Github Desktop
- Github
- jsDeliver

## Creating the Repo and setting up Version Control

### In Bert Github Account

- Create New Repo
- Click Set Up in Desktop Button

### In Github Desktop
- Click Clone
- Click Open in Visual Studio Code

## To Deploy Code to Github

### In Github Desktop
- Write description
- Click Commit to Main
- Click Publish Branch
- Or Push Origin

## To pull files from JSDeliver

Use the following code structure:

`<script defer src=”https://cdn.jsdelivr.net/gh/user/repo@version/file”></script>`

Populated would look like:

[https://cdn.jsdelivr.net/gh/bertagency/js-deployment-testing/readme.md](https://cdn.jsdelivr.net/gh/bertagency/js-deployment-testing/readme.md)

## Versioning

All Versions will be created and managed in the Github repository interface

## To Create a Version 1

### In the Github Repository:
- In the right of the list of files, click Release
- Click Draft a new release
- Choose a Tag or create a new one eg v1.0.0
- Add Version Title and Release Notes
- Click Publish Release

### Result:
You will be able to view v1 of the code at:

`https://cdn.jsdelivr.net/gh/user/repo@version/file`

Eg:
`https://cdn.jsdelivr.net/gh/bertagency/js-deployment-testing@1/readme.md`

## Purge jsDeliver to refresh on all sites using this code
https://www.jsdelivr.com/tools/purge


### Reference:
[https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository](https://docs.github.com/en/repositories/releasing-projects-on-github/managing-releases-in-a-repository)

## Collaboration
Instructions for Collaboration will be added here.

## Appendix

### Naming Conventions for Versioning Code

#### Eg v1.5.2

- V1.0.0 Major Version -  API methods methods or major features are now included / not included. Breaking changes change this version.
- 1.5.0 Minor Version - Minor changes - does not break API. Eg improvements and non breaking new features.
- 1.5.2 Patch - bug fixes

