---
title: GitLab
owner: London Services
---

## Installation

To install GitLab for [Pivotal Cloud Foundry&reg;](https://network.pivotal.io/products/pivotal-cf) (PCF), follow the procedure for installing Pivotal Ops Manager tiles:

1. Download the product file from [Pivotal Network](https://network.pivotal.io/products/p-gitlab).
1. Upload the product file to your Ops Manager installation.
1. Click **Add** next to the uploaded product description in the Available Products view to add this product to your staging area.
1. Click the newly added tile to review any configurable options.
1. Populate all of the mandatory configuration options for MySQL, Redis, SMTP, etc.
1. Click **Apply Changes** to install the service.
1. Once deployed, visit the URL for the web dashboard. By default, this is `https://gitlab.apps.my-pcf.com`.
1. The first time, log in with the following information:
  1. Username of `root`
  1. Password of `5iveL!fe`
  1. Configure a new password for the root account, and keep this safe.

## Adding new users

To add new users to the product:

1. Visit the web dashboard. By default, this is `https://gitlab.apps.my-pcf.com`.
1. Click **Create new user**.
1. Populate all of the required details.
1. Check email for confirmation mail.
1. Confirm email address and log in.
