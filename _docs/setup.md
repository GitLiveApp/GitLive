---
title: Setting up GitLive
subtitle: This section will guide you in setting up GitLive for your organization or account.
author: friedrich
tags: [setup, signin]
---

### Pre-requisites

In order to use GitLive, you are required to use a repository hosting service that we support. These are currently GitHub, Bitbucket, GitLab and Azure DevOps. We also support GitLab self-hosted repositories.

If you are unfamiliar with repository hosting services please read [Github's help section](https://help.github.com/en) in order to get familiar with them.

Clone any of your desired repositories and open them in your IDE.

## As an administrator

As an Administrator, you need to grant access to the desired repositories you want to use the GitLive plugin/extension with. This requires installing the GitLive app on your organization level or account level.

If you are using a cloud repository hosting service (e.g. [github.com](https://github.com/)), proceed to the [setup guide for administrators (Cloud Repository Hosting Services)](/docs/admin) to grant permissions to the relevant repositories. If you are using a self-hosted repository (Currently GitLive only supports GitLab self-hosted), proceed to the [setup guide for administrators (GitLab Self-Hosted Repository)](/docs/admin-self-hosted).

After installing the GitLive app on your repository hosting service, ask your team members to install the plugin in their respective IDEs and authenticate with GitLive as shown in the [setup guide for team members](/docs/teammember).

## As a team member

Given that the Admin of your repository has followed the instructions as in the [setup guide for administrators(Cloud Repository Hosting Services)](/docs/admin) or the [setup guide for administrators (GitLab Self-Hosted Repository)](/docs/admin-self-hosted) , an individual team member needs to authenticate themselves. To do this, you must open the cloned repository in your IDE and authenticate with your repository hosting service as demonstrated in the [setup guide for team members](/docs/teammember).

