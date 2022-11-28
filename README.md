# GitLive Documentation

# Development teams merge faster with GitLive

[![Video](https://uploads-ssl.webflow.com/6033cf9dce54c65d97d57571/636d19a8d7aa4aa2cb1888cf_poster-vsc.png)](https://git.live/video)

<br>

GitLive helps you and your fellow contributors merge faster by avoiding conflicts and encouraging eager and continuous code review directly inside the IDE.

<br>

## **Do not let merge conflicts break your flow**

**Indicators in the gutter of your editor show the changes others are making.** Computed from all active branches, the indicators update as you and your team code together.
**Get notified the moment you make a change that conflicts with another branch.** Compare their changes to your own and cherry‑pick individual changes directly into your local files.

![Merge Conflicts](https://uploads-ssl.webflow.com/6033cf9dce54c65d97d57571/636c013af698e1cb81063bd0_MC_VSC_860x605.gif) 

<br>

## **Get the ultimate perspective on all work in progress**

**Perform eager and continuous code review directly in your IDE with the team view.** See who is online, their active branches and changes in a single repository or across your organization, updated in real‑time.
**Get notified when you fall behind the main branch or your tracking branch.** Inspect the changed files in the repository view to know if they will merge cleanly with your own local changes before you pull.

![Team View](https://uploads-ssl.webflow.com/6033cf9dce54c65d97d57571/636d1b95b0c59edf89f413ae_TT_VSC_860x605.gif)



<br>

## **Let your team know what you are working on**

**Connect your issue tracker to see each other's current issue in the team view.** The issue you are working on is determined by your current branch and updates automatically.
**View your current issue and select another issue to work on via the status bar.** Switching issues will check out an existing feature branch or create a new one for you if needed.

![Issue Tracker](https://uploads-ssl.webflow.com/6033cf9dce54c65d97d57571/636c0138cfaef237d50a93cc_IT_VSC_860x605.gif)  

<br>

## Contents
1. Installation
   1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/installation-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/installation-jetbrain.md)
   1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/installation-vscode.md)
1. Setting up GitLive
   1. As an Admin
      1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/admin-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/admin-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/admin-vscode.md)
   1. As a Team Member
      1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/teammember-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/teammember-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/teammember-vscode.md)
1. Account Management
      1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/account-management-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/account-management-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/account-management-vscode.md)
1. Visibility
   1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/visibility-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/visibility-jetbrains.md)
   1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/visibility-vscode.md)
   1. Privacy
      1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/privacy-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/privacy-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/privacy-vscode.md)
1. Video Calling
   1. [Android Studio](https://github.com/GitLiveApp/GitLive/blob/master/_sections/videocalling-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/GitLive/blob/master/_sections/videocalling-jetbrains.md)
   1. [VS Code](https://github.com/GitLiveApp/GitLive/blob/master/_sections/videocalling-vscode.md)

<br />

## Contributing to GitLive
We're a tool built for developers, by developers. So your contributions are important to us! Please review this section to make the process of contributing as smooth and efficient as possible.

### Reporting an Issue
GitLive uses [Github Issue Tracking](https://github.com/GitLiveApp/gitlive/issues) to track issues (mainly bugs). If you've found a bug, this is the place to start.
1. You'll need to create a (free) GitHub account in order to submit an issue.
1. Search the current issues to see if the bug has already been reported.
1. If it hasn't, you can [Open a new Issue](https://github.com/GitLiveApp/gitlive/issues/new).
   1. Please include as much information as possible - a title and a clear description at the very least.


### Feature Requests
Feature requests are welcome. But please take a moment to find out whether your idea fits with the scope and aims of the project, and provide as much detail as you can.

### Improving the Documentation
If there are any improvements you would like to see to our documentation, you can also use the Github issue tracking system. Our documentation is all open source, so if there are any improvements you would like to make yourself, you can do so via a pull request, which we will then review.

### Serving your Changes Locally

Install the bundler if you don't have it already.
```bash
gem install bundler
```

Install the dependencies with [Bundler](http://bundler.io/):

```bash
bundle install
```

Run the following to serve the site locally:
```bash
bundle exec jekyll serve
```

Now you will be able to view your changes locally by going to:
```bash
http://localhost:4000
```

You can find more on [Deployment Methods](https://jekyllrb.com/docs/deployment-methods/) page on Jekyll website.

