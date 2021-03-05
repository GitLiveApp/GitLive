---
title: Android Studio
tab: android
---

### Overview

GitLive allows you to see your teammates’ changes to a file in the gutter of your editor and get notified of conflicts as soon as they occur even across branches and uncommitted changes

![jetbrains Gutter](/uploads/jetbrains-gutter-cherry-pick.gif "jetbrains Gutter"){:class="screenshot"}
### Gutter indicators for teammate’s changes
GitLive adds gutter indicators to show you where your teammate’s have made changes to the file you have open, these update in real-time as you and your teammates are editing.

Insertions are represented by a green arrow, modifications are denoted by a blue line and deletions by a  grey line.

![Android Studio Gutter](/uploads/android-studio-gutter-teammate.jpeg "Android Studio Gutter"){:class="screenshot"}

### Conflict Indicators
If your teammate’s changes are conflicting with your local changes, they are accompanied by the bright red conflict indicator. These conflicts can be uncommitted local changes you have not pushed yet or existing changes on your branch which are conflicting with their branch and/or uncommitted changes.

![jetbrains Red Gutter](/uploads/jetbrains-red-gutter.jpg "jetbrains Red Gutter"){:class="screenshot"}


### Review your teammates’ changes
Once a line change indicator appears in the gutter, hovering over the affected line launches a popup which shows your teammates changes on the concerned lines, the connected issue they are working on and the code they have added.

![jetbrains Gutter Popup](/uploads/jetbrains-gutter-popup.jpg "jetbrains Gutter Popup"){:class="screenshot"}

### Cherry Picking
Merge conflict detection can be combined with GitLive’s Cherry Picking feature. When spotting a teammate’s change on lines you need to apply changes to as well, you might want to apply their changes first to prevent a conflict from emerging. Simply cherry pick your teammate’s changes in the popup which will grab the changes and apply them to your working copy. You can do this by selecting the cherry icon.

![jetbrains Gutter Cherry Pick](/uploads/jetbrains-gutter-cherry-pick.jpeg "jetbrains Gutter Cherry Pick"){:class="screenshot"}

### Hiding teammates’ gutter indicators
By default the gutter indicators will show for a file as long as one or more teammates have changes in the same file, but you have the option to hide these indicators if they are competing with other annotations in the gutter. Toggle the indicators on and off by right-clicking the gutter.

![jetbrains Toggle](/uploads/jetbrains-toggle.jpeg "jetbrains Toggle"){:class="screenshot"}
