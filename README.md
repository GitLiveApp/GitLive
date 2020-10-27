# GitLive Documentation

GitLive allows you to view, share and edit code together with your team, live, across VS Code and JetBrains
* Check who is online from your team and which repositories, branches and issues they are working on
* Inspect and cherry-pick your teammates' local changes without performing a commit-push-fetch-merge cycle
* Open a live view of the file a teammate is working on and edit together
* Privacy-first: Easily control what you share including your online status, activity and local changes
<br />

![Collaborative Coding Gif](https://github.com/GitLiveApp/blog/blob/master/assets/images/posts/2020/collabv3.gif)
<br />

## Contents
1. Installation
   1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/installation-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/installation-jetbrain.md)
   1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/installation-vscode.md)
1. Setting up GitLive
   1. As an Admin
      1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/admin-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/admin-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/admin-vscode.md)
   1. As a Team Member
      1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/teammember-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/teammember-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/teammember-vscode.md)
1. Account Management
      1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/account-management-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/account-management-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/account-management-vscode.md)
1. Visibility
   1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/visibility-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/visibility-jetbrains.md)
   1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/visibility-vscode.md)
   1. Privacy
      1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/privacy-android-studio.md)
      1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/privacy-jetbrains.md)
      1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/privacy-vscode.md)
1. Pair Programming
   1. [Android Studio](https://github.com/GitLiveApp/documentation/blob/master/_sections/pairprogramming-android-studio.md)
   1. [Other JetBrains IDE's](https://github.com/GitLiveApp/documentation/blob/master/_sections/pairprogramming-jetbrains.md)
   1. [VS Code](https://github.com/GitLiveApp/documentation/blob/master/_sections/pairprogramming-vscode.md)

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

Follow this process if you'd like to make a change to the documentation:

1. Clone the Documentarion Repository:

   ```bash
   # Clone the repo 
   git clone git@github.com:GitLiveApp/gitlive.git
   # Navigate to the newly cloned directory
   cd gitlive

2. Get the latest changes from the master branch:

   ```bash
   git checkout master
   git pull origin master
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your feature, change, or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Commit your changes in logical chunks. Please adhere to these [git commit
   message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
   or your code is unlikely be merged into the main project. Use Git's interactive rebase
   feature to tidy up your commits before making them public.

5. Locally merge (or rebase) the master branch into your topic branch:

   ```bash
   git rebase origin master
   ```

6. Push your changes to your branch:

   ```bash
   git push origin <topic-branch-name>
   ```

7. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.

<br />
<br />

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

