---
title: Visual Studio Code
tab: vscode
---

### Overview

GitLive allows you to see your teammates’ changes to a file in the gutter of your editor and get notified of conflicts as soon as they occur even across branches and uncommitted changes

![VScode Gutter](/uploads/VScode-gutter-cherry-pick.gif "VScode Gutter"){:class="screenshot"}

### Gutter indicators for teammate’s changes
GitLive adds gutter indicators to show you where your teammate’s have made changes to the file you have open, these update in real-time as you and your teammates are editing.

Insertions are denoted in green, modifications in blue and deletions in red.

![VSCode Gutter](/uploads/vscode-gutter-teammate.jpg "VSCode Gutter"){:class="screenshot"}

### Conflict Indicators
If your teammate’s changes are conflicting with your local changes, they are accompanied by the bright red conflict indicator. These conflicts can be uncommitted local changes you have not pushed yet or existing changes on your branch which are conflicting with their branch and/or uncommitted changes.

![VSCode Red Gutter](/uploads/vscode-red-gutter.jpg "VSCode Red Gutter"){:class="screenshot"}


### Review your teammates’ changes
Once a line change indicator appears in the gutter, hovering over the affected line launches a popup which shows your teammates changes on the concerned lines, the connected issue they are working on and the code they have added.

![VSCode Gutter Popup](/uploads/vscode-gutter-popup.jpg "VSCode Gutter Popup"){:class="screenshot"}

### Cherry Picking
Merge conflict detection can be combined with GitLive’s [cherry picking](/docs/cherrypicking){:class="internal-link"} feature. When spotting a teammate’s change on lines you need to apply changes to as well, you might want to apply their changes first to prevent a conflict from emerging. Simply cherry pick your teammate’s changes in the popup which will grab the changes and apply them to your working copy. You can do this by selecting “Cherry Pick these Changes”.

![VSCode Gutter Cherry Pick](/uploads/vscode-gutter-cherry-pick.jpeg "VSCode Gutter Cherry Pick"){:class="screenshot"}

### Hiding teammates’ gutter indicators
By default the gutter indicators will show for a file as long as one or more teammates have changes in the same file, but you have the option to hide these indicators if they are competing with other annotations in the gutter. Toggle the indicators on and off by clicking the GitLive icon in the editor title menu bar.

![VSCode Toggle](/uploads/vscode-toggle.jpeg "VSCode Toggle"){:class="screenshot"}
