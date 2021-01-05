---
title: Visual Studio Code
tab: vscode
---

### Overview

GitLive integrates with Jira, GitHub Issues, Bitbucket Issues, Azure DevOps Work Items and GitLab Issues (with Trello coming soon) allowing you to share what issue you are currently working on with your teammates based on your current branch.

To connect an issue tracker to your GitLive organisation, follow the steps as shown in the [as an admin](/docs/admin){:class="internal-link"} section.


### Select an Issue
When on the default branch (e.g. main) of a repository, GitLive will prompt you to select an an issue to start work on. You can choose from the issues already assigned to you, assign an existing issue or create a new issue.

![Issue Tracker Workflow](/uploads/vscode-select-issue.gif "Issue Tracker"){:class="screenshot"}


### Automatic Branch Creation
After selecting an issue, a feature branch named after that issue automatically gets created (if it does not already exist) and checked out from the default branch, meaning you are ready to get to work straight away.

![New Branch Created](/uploads/vscode-issue-selected.jpeg "New Branch Created"){:class="screenshot"}


### Change Issue
The issue you are currently working on is displayed in the status bar. You can change issues anytime by clicking this status bar item. This will check out a new branch for the new issue you have selected.
![Switch Issue](/uploads/vscode-switch-issue.jpeg "Switch Issue"){:class="screenshot"}
