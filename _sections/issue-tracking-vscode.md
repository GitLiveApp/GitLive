---
title: Visual Studio Code
tab: vscode
---

### Overview

GitLive integrates with Jira, GitHub Issues, Bitbucket Issues, Azure DevOps Work Items and GitLab Issues, allowing you to share which issue you are currently working on with your teammates based on your current branch.

To connect an issue tracker to your GitLive organisation, follow the steps as shown in the [as an admin](/docs/admin){:class="internal-link"} section.

![View Issues Others are Working on](/uploads/vscode-issue-tracker-visibility.jpg "View Issues Others are Working on"){:class="screenshot"}


### Select an Issue
When on the default branch (e.g. master) of a repository, GitLive will prompt you to select an issue to start work on. You can choose from the issues already assigned to you, assign an existing issue or create a new issue.

![Issue Tracker Workflow](/uploads/vscode-select-issue.gif "Issue Tracker"){:class="screenshot"}


### Automatic Branch Creation
After selecting an issue, a feature branch named after that issue automatically gets created (if it does not already exist) and checked out from the default branch, meaning you are ready to get to work straight away.

![New Branch Created](/uploads/vscode-issue-selected.jpeg "New Branch Created"){:class="screenshot"}


### Change Issue
The issue you are currently working on is displayed in the status bar. You can change issues anytime by clicking this status bar item. This will check out a new branch for the new issue you have selected.

![Switch Issue](/uploads/vscode-switch-issue.jpeg "Switch Issue"){:class="screenshot"}


### Connect An Issue to an Existing Branch
If you are on a branch which is not yet connected to an issue, GitLive will prompt you to connect an issue.

You can select from the issues already assigned to your on your issue tracker, assign an existing issue to yourself or create a new issue for the branch. You also have the option to ignore that particular branch, in which case, you won’t be prompted to connect the branch to an issue again.

![Connect Issue](/uploads/vscode-connect-issue-to-branch.jpg "Connect Issue"){:class="screenshot"}

[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/blob/master/_sections/issue-tracking-android-studio.md){:class="uk-button uk-button-success"}