---
title: Visual Studio Code
tab: vscode
---
### Overview

GitLive focuses on improving developer visibility with what we’re dubbing enhanced presence, to help developers work more effectively as a team.

<table>
<thead>
<tr>
   <th>Presence</th>
   <th>Questions Answered</th>
  </tr>
</thead>
 <tbody>
  <tr>
   <td>Traditional</td>
   <td>
    Who is online?<br />
    Who is online but not currently active (away)?
   </td>
  </tr>
  <tr>
   <td>Enhanced<br />
    (with GitLive)
   </td>
   <td>
    Who is online or away?<br />
    Which repositories are they working on?<br />
    What branch are they currently on?<br />
    What files have they changed in their working copy?
   </td>
  </tr>
 </tbody>
</table>

### Who's Online?

The GitLive window in VS Code lists the teammates of a given organization. Being online or not is denoted by the white dot being filled in.

![See who else is online](/uploads/visibility-online-vscode.jpeg "Online Visibility"){:class="screenshot"}

### Which repositories are they working on?

GitLive displays all of your teammates’ working copies for the repositories that you share write access to. If your teammate is not active in a working copy, its last known state is still visible if it contains uncommitted changes.

In the screenshot below **SuDa2103** shares access with you on a repository called **sample-repo**. He is currently working on the **sample-repo** repository as denoted by the dot next to the repository name.

![See which repos your teammates are on](/uploads/visibility-repo-vscode.jpeg "Which Repo"){:class="screenshot"}

### What branch are they currently on?

As useful as it is to know a fellow developer is online, a common question teammates ask each other is ***what branch are you on?***
Enhanced presence gives you awareness on the branch your teammate is currently working on. As can be seen in the screenshot below **SuDa2103** is currently checked out on the **bugfix** branch within the **sample-repo** repository.


![See which branch your teammates are on](/uploads/visibility-branch-vscode.jpeg "Which Branch"){:class="screenshot"}

To break it down even further you can actually see the exact file your teammate is currently active on by the dot next to the files name. Below **SuDa2103** is currently active in file **BluetoothService.kt**.

![See which file your teammates are on](/uploads/visibility-file-vscode.jpeg "Which File"){:class="screenshot"}


### What did your teammates change locally compared to their latest pull?

Furthermore, you can drill down into an individual teammate’s working copy local changes for quick and easy problem-solving. This allows you to seamlessly understand what your teammate is referring to instead of going through a cumbersome commit-push-fetch cycle. The GitLive window shows you your teammate’s working copy changes relative to his latest pulled remote state, visualised by the number of lines added and deleted (denoted by the + and - symbols). As can be seen below, **SuDa2103** has edited the file **BluetoothService.kt** locally. The "+" symbols next to the file implies that he has added three lines of code in this files locally compared to his latest pulled remote state.

![See the changes in their working copy](/uploads/visibility-working-copy-vscode.jpeg "Working Copy Changes"){:class="screenshot"}

### Live Difference View

You can also use GitLive to see which particular lines are different in your teammates working copy, relative to yours. All you have to do is click on a filename, and a diff view visualising your teammates local changes compared to his latest pulled remote state opens up.

![See the changes in their working copy](/uploads/vscode-diff-view.gif "Diff View"){:class="screenshot"}


[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/edit/master/_sections/visibility-vscode.md){:class="uk-button uk-button-success"}

