---
title: Visual Studio Code
tab: vscode
---

### Overview

In this quick guide you will learn how to install the GitLive app on your self hosted Gitlab instance as an administrator.

### Steps for authenticating
As an administrator, you are required to install the GitLive app on the group level and grant it access to the repositories that you would like to use GitLive with. Note that your instance will need to be accessible from the internet in order for the integration to work correctly.
### Step 1
* Install the plugin as explained in the [installation section](/){:class="internal-link"}.
* Open up a clone of the repository that you want to use GitLive with.
* Then, you will see the following prompt in the GitLive window:

![Configure Server](/uploads/vscode-gsh-configure-server.jpg "Configure Server"){:class="screenshot"}


### Step 2

After clicking on "Configure new GitLab server", follow the setup instructions. You'll start by adding a new OAuth 2.0 application in GitLab, this will allow you to set the right scopes, and get the GitLab Application ID and Secret, which are needed in GitLive.

![Self hosted form](/uploads/gsh-form-empty.jpg "Self hosted form"){:class="screenshot"}

When adding a new application, it's important to make sure that you are selecting the correct options, as specified in the instructions.

![Form Options](/uploads/gsh-form-fill.jpg "Form Options"){:class="screenshot"}

### Step 3

The next step is to authenticate and install your newly created GitLab application on the group of your choice.

<table class="table-custom">
  <tbody>
        <tr>
            <td class="td-custom">
              <img src="/uploads/gsh-authorise.jpg">
            </td>
            <td class="td-custom">
              <img src="/uploads/gsh-where.jpg">
            </td>
        </tr>
  </tbody>
</table>

### Step 4

Finally, you will see a screen showing you that GitLive has been installed successfully, with the option to connect your issue tracker to enable our [issue tracking integration](/gitlive-9.0).

![Successful Self Hosted Installation](/uploads/gsh-successful.jpg "Successful Self Hosted Installation"){:class="screenshot"}

### You're all set!

* You can now have your team members install the plugin and authenticate. See the  [setting up as a team member section](/docs/teammember){:class="internal-link"}.


[Suggest an Edit to this Page](https://github.com/GitLiveApp/GitLive/edit/master/_sections/self-hosted-admin-vscode.md){:class="uk-button uk-button-success"}


