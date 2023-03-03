# Purpose

This Documentation aims to explain the following procedures for a simple minimum working standard to collaborate on and deploy scripts. This documentation is written for those with an entry level of understanding of version control and git.

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

### To add a collaborator (eg remote freelancer)
#### In Github Website Repo
- Settings
- Collaborators
- Add People

### Working with Issues

This will keep a clear technical brief for this issue separate from the main branch.
Issues will be assigned to collaborators and only this developer will work on this code.
Normally we will create a separate script for each issue and assign them to just one developer per issue at any one time. This will mean that there will be very few conflicts. To avoid conflicts, Issues will usually create an entirely new js file which will have distinct functionality.

### In Github Repo Account
- Go to Issues
- Give title and description
- Use Markdown and write a User Story with clear Acceptance Criteria
- Click Submit New Issue

### Assigning to a Collaborator
- Click to view the Issue
- Right Sidebar - Assignees
- Assign to a Collaborator

### Working on a Branch

### Creating a Branch
### As A Collaborator
- In Github Desktop
- Under Main
- Enter a clear title for the new Branch
- Click Create Branch: Branch Name ‘from Main’
- You will only need to create a Branch once. This Branch will be for you to work on as a collaborator, or for a specific issue to be worked on

### Working on a Branch
- In Github Repo
- View the Branch
- Click Open in Github Desktop
- Select the Branch to edit
- Click open in Visual Studio Code
- Create fix for the code
- Commit to (Branch Name)
- Click Push Origin

### Completing Work on a Branch
When completed:
### As a Collaborator
- Navigate to the Branch you worked on
- Create a pull request

### As Repository Owner
### To review and merge code
- May need to click Fetch Origin to review any other Branches and changes
- Switch to the right Branch
- Open in Visual Studio Code
- Review the code

- Close the issue with a comment.

### How to Merge Branches
- Review the Pull Request
- Confirm there are no conflicts or deal with each conflict
- Click merge pull request
- Confirm merge

All changes from the Branch will be merged with the Main Branch
The Branch will still exist


## Appendix



### Reference
[https://www.freecodecamp.org/news/basic-html5-template-boilerplate-code-example/](https://www.freecodecamp.org/news/basic-html5-template-boilerplate-code-example/)

### Naming Conventions for Versioning Code

#### Eg v1.5.2

- V1.0.0 Major Version -  API methods methods or major features are now included / not included. Breaking changes change this version.
- 1.5.0 Minor Version - Minor changes - does not break API. Eg improvements and non breaking new features.
- 1.5.2 Patch - bug fixes

### Running Code Locally
- Check Live Preview by Microsoft is installed
- Click Go Live
- Scripts for example will be accessible by adding the following to any web project:
`<script defer src="http://localhost:5500/{FILE_PATH}.js"></script>`

### Tools

### VSCode Extensions we use

#### Live Preview by Microsoft
- To run code locally using VScode

#### Prettier

#### ESLint