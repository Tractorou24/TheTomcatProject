# CONTRIBUTING

This is TBD. Please feel free to propose ideas to flesh this out.

## Contributing to TheTomcatProject Repository

### 1) Fork the repo

The first step is to fork the repo (repository).

1. Click on the `Fork` button in the top right corner of the project's GitHub page.
   This creates a fork of the repository under your github account you can modify at will.

### 2) Clone the repo

The first time, you will need to install the github desktop app, open it and login with your GitHub account info. (If you know how to use CLI GIT, this guide is probably too basic for you.)

1. Open the GitHub Desktop App. Click `File` > `Clone Repository`.
2. Click on the fork under your account, and pick an empty folder for it to clone into. (Caution: its a couple gigs of data.)
3. Click `Clone`.
   Now you have a copy on your PC of TheTomcatProject Project Dev Files.

### 3) Select the base branch

Click on `Current branch` at the top, select the branch you want to work with as a base. (Usually, should be current working branch (i.e. `master`.)

### 4) Create a branch

Click on `Current branch` at the top, click `New Branch`, and create a branch. Make sure it's descriptive and follows the guidelines below.

### 5) Make the change

Navigate to the folder you cloned the repo to, then make the change(s) you want to contribute back.

### 6) Commit the change

After completing your desired change, go back to github desktop app and complete the commit title and descriptions fields. title should be brief, description should be verbose. Commit frequently, so you have lots of points to roll back to if something doesn't work out.

### 7) Push the change

The next step is to synchronize your local changes with your repository on GitHub. You need to push your changes to GitHub. Click the button that displays `Publish branch` to sync changes. Now you have the same copy of this branch on your computer as well as on GitHub.

### 8) Submit a Pull Request

This is where you really document the nitty gritty of what you did and why you did it.

A Pull Request notifies the project maintainers that you have some work that they should review and eventually add to the project.

Go to the main page of your fork on GitHub and click on the highlighted PR message with a green button displaying `Compare & pull request`.

Write a title and in the comments section summarize the work you did.

- Use our template that shows when you create a PR.
- Be verbose.
- Be detailed.
- Add pictures describing your change.
- Tell us why it changed.
- Reference an issue.
- Use the checklist in the PR.

Click `Create pull request` and leave the box checked that says `Allow edits from maintainers`.

## Aw crap, I need to fix my PR (Or a reviewer requested changes.)

- Thats easy! Just rebase your commit against the same branch the PR is against and it will apply it to the PR. (Try not to open a new PR unless explicitly instructed to by repository maintainers.)

## Branches

### Master branch

The Master branch is the current stable state of the project. This branch will be commited each time a PR have recieved the clearance from maintaniers. (As a contributor, do not commit to Master. Ever. It will not work.)

### Version branch

A version branch contains everything per version.

## Commits

### Commit Frequencies

Commits shall be pushed to remote (the GitHub Repo) at least daily on any day work has taken place, but preferably pushed as each commit is made, real-time. This policy will help eliminate overlap and conflicting dependencies.

### Commit Messages

- The commit subject should be capitalized.
- The commit subject should be no more than 50 characters in length (with wiggle room up to 72 characters in length as a hard max.)
- The commit subject should not contain punctuation at the end of it.
- The commit subject should use the imperative mood (i.e. "Clean your room", "Close the door", etc.)
- A properly formed Git commit subject line should always be able to complete the following sentence:
  - If applied, this commit will **your subject line here**
  - For example:
    - If applied, this commit will _Refactor subsystem X for readability_
    - If applied, this commit will _Update getting started documentation_
    - If applied, this commit will _Remove deprecated methods_
- The commit message body should use proper capitalization and punctuation.
- The commit message body should be detailed enough that the reader can understand the changes made.
- The commit message body can reference other issues and pull requests at the end.
