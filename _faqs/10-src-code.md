---
title: Does GitLive store source code from the Git repos it is accessing?
categories: [support]
---

No, we only store patches of the uncommitted changes. These files only contain the differences between the teammate's working copy version of a file and the latest repository version. **We do not store complete copies of the source files**. Once a teammate pushes their changes the patch file is permanently deleted from our database.
