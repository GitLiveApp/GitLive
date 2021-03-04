---
title: Android Studio
tab: android
---

### Overview

GitLive allows you to detect and resolve merge conflicts as they occur, inside your IDE.
This prevents the need to go back over the code and resolve merge conlficts later.

### See teammates changes in your IDEs gutter
Users have access to a toggle that allows them to choose whether they want change indicators to appear in the gutter.


Once switched on, GitLive adds line change indicators in the gutter for you to keep track of your teammates changes across different branches. These changes refer to unpushed code of your teammates. The author of each change is indicated by your teammates icon.

### Spot Merge Conflicts
If your teammate’s changes are conflicting with your local changes they are accompanied by the red conflict indicator.


### Hover over Affected Lines
Once a line change indicator appears in the gutter, clicking on the icon launches a popup which shows your teammates changes on the concerned lines, the connected issue they are working on and the code they have added.


### Cherry Picking
Merge conflict detection can be combined with GitLive’s Cherry Picking feature. When spotting a teammate’s change on lines you need to apply changes to as well, you might want to apply their changes first to prevent a conflict from emerging. Simply cherry pick your teammate’s changes in the popup which will grab the changes and apply them to your working copy. You can do this by selecting the cherry icon.
