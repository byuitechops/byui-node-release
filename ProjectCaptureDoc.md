# Project Capture Document for BYUI Node Release
#### *Author: Seth Bolander*
#### *Stakeholder(s): Josh McKinney*
#### *Date: 2019 April 15, 02:27 PM*

## Background

When a branch is ready to merge with master there are several steps that must be taken: Ensuring documentation is up to date, committing all files and cleaning working tree, pushing to the checked out branch, and then making a merge request in GitHub. If these steps are not followed properly it can cause fatal errors in your repository and potentially undo work on the current commit. The TechOps team needs a way to make this process clean, easy, and show changes on master. The team needs an automated tool or command that can run all the correct commands and document those changes in package.json and/or commit history.

-----

## Definition of Done

A single command that will run all of the needed git commands correctly and automatically "release" the new updates to the master branch of the repository the command is called on. This command could/would be included in the package.json of each project as a "version" script to be run so as to allow for standard use between projects.

-----

# Requirements

### General Requirements

### Input Requirements

No inputs are needed.

---

### Output Requirements
#### Destination

All output is directly pushed to the repository's master branch and remote master branch.

### User Interface

#### Type:

CLI command, potentially with flags. Or to be included as NPM "version" script.

-----

## Expectations

### Timeline

### Best Mode of Contact

### Next Meeting


### Action Items
<!-- Recap Meeting -->
#### TechOps
#### Stakeholder

-----

#### *Approved By:* 
#### *Approval Date:*
