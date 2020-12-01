---
title: Android Studio
tab: android
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
    How active have they been in the last 24 hours?<br />
    Which repositories are they working on?<br />
    What branch are they currently on?<br />
    What files have they changed in their working copy?
   </td>
  </tr>
 </tbody>
</table>

### Who's Online?

The GitLive window in your IDE lists the teammates of a given organization. Being online is denoted by a little green dot.

![See who else is online](/uploads/android-studio-visibility-online.jpeg "Online Visibility"){:class="screenshot"}

### Which repositories are they working on?

GitLive displays all of your teammates’ working copies for the repositories that you share write access to. If your teammate is not active in a working copy, the last known state of the file will be visible, including uncommitted changes. 

In the screenshot below,  **SuDa2103** shares access with you to the repository called **sample-repo**. He is currently working on the **sample-repo** repository as denoted by the dot next to the repository name.

![See which repos your teammates are on](/uploads/android-studio-visibility-repo.jpeg "Which Repo"){:class="screenshot"}

### What branch are they currently on?

As useful as it is to know a fellow developer is online, a common question teammates ask each other is ***what branch are you on?***
With the enhanced presence you can see the branch your teammate is currently working on. As can be seen in the screenshot below,  **SuDa2103** is currently checked out on the **bugfix** branch within the **sample-repo** repository.

![See which branch your teammates are on](/uploads/android-studio-visibility-branch.jpeg "Which Branch"){:class="screenshot"}

The white dot next to the file name indicates that your teammate is active in that particular file. Below **SuDa2103** is currently active in file **BluetoothService.kt**.

![See which file your teammates are on](/uploads/android-studio-visibility-file.jpeg "Which File"){:class="screenshot"}

### What did your teammates change locally compared to their latest pull?

Furthermore, you can drill down into an individual teammate’s working copy local changes for quick and easy problem-solving. This allows you to seamlessly understand what your teammate is referring to instead of going through a cumbersome commit-push-fetch cycle. The GitLive window shows you your teammate’s working copy changes relative to his latest pulled remote state, visualised by the number of lines added and deleted (denoted by the + and - symbols). As shown below, **SuDa2103** has edited the file **BluetoothService.kt** locally. The "+" symbols next to the file indicate that he has added three lines of code in this file locally compared to his latest pulled remote state.

![See the changes in their working copy](/uploads/android-studio-working-copy.jpeg "Working Copy Changes"){:class="screenshot"}

### Live Difference View

You can also use GitLive to see which particular lines are different in your teammate's working copy, relative to yours. All you have to do is click on a filename, and a diff view visualising your teammate's local changes compared to his latest pulled remote state opens up.

![See the changes in their working copy](/uploads/jetbrains-diff-view.gif "Diff View"){:class="screenshot"}

### How active have they been in the last 24 hours?

Finally, GitLive's window also introduces a feature dedicated to flexible teams which need a sense of working presence. The activity graph beside each developer's name displays how active they have been in the last 24 hours.

Time runs from left to right with now being on the left-most side; you can see the exact time on rollover.
It’s important to note the graph isn’t a reflection of how hard someone is working; for instance, tracking down a bug vs tweaking UI code vs writing unit tests are likely to produce widely different looking graphs.

The activity graph aims to give a team with flexible working hours or working remotely an indication as to how their teammate’s tasks are progressing.

![See how active others have been in the last 24 hrs](/uploads/android-studio-visibility-activity.jpeg "Activity Visibility"){:class="screenshot"}


[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/edit/master/_sections/visibility-android-studio.md){:class="uk-button uk-button-success"}




