---
title: GitLab
---

# Connecting via Git
Once a user has configured their repositories they'll be presented with the details on how to connect with Git.

## HTTPS

You can perform all git actions against your repositories using the registered URL.

By default this is `https://gitlab.apps.my-pcf.com`

## SSH

SSH access is possible through following the steps detailed [here](gitlab/ssh.html).

The current SSH experience is not optimal and requires some additional configuration outside of the tile by the Operator. In future versions of the tile we are looking to address this by being able to use a URL registered automatically during deployment of the tile for SSH access.
