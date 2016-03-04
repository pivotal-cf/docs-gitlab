---
title: GitLab
owner: London Services
---

This is documentation for the [GitLab service for Pivotal Cloud Foundry&reg;](https://network.pivotal.io/products/p-gitlab).

## Product snapshot

<dl>
<dt>Current GitLab for <a href="https://network.pivotal.io/products/pivotal-cf">Pivotal Cloud Foundry&reg;</a> Details</dt>
<dd><strong>Version</strong>: 1.0.1 </dd>
<dd><strong>Release Date</strong>: 14th December 2015</dd>
<dd><strong>Software component version</strong>: GitLab Enterprise 7.14.3</dd>
<dd><strong>Compatible Ops Manager Version(s)</strong>: 1.6.x, 1.5.x</dd>
<dd><strong>Compatible Elastic Runtime Version(s)</strong>: 1.6.x, 1.5.x</dd>
<dd><strong>vSphere support?</strong> Yes</dd>
<dd><strong>AWS support?</strong> Yes</dd>
<dd><strong>OpenStack support?</strong> Yes</dd>
</dl>

## Upgrading to the Latest Version

Consider the following compatibility information before upgrading GitLab for Pivotal Cloud Foundry&reg;.

<table border="1" class="nice">
<tr>
  <th>Ops Manager Version</th>
  <th>Supported Upgrades from Imported GitLab Installation</th>
</tr>
<tr>
  <th>1.6.x, 1.5.x and 1.4.x</th>
  <td><ul>
      <li>From 0.1.1 BETA to 1.0.1</li>
    </ul>
  </td>
</tr>
</table>

## Install via Pivotal Operations Manager

To install GitLab for PCF, follow the procedure for installing Pivotal Ops Manager tiles:

1. Download the product file from [Pivotal Network](https://network.pivotal.io/).
1. Upload the product file to your Ops Manager installation.
1. Click **Add** next to the uploaded product description in the Available Products view to add this product to your staging area.
1. Click the newly added tile to review any configurable options.
1. Click **Apply Changes** to install the service.

## Security
The following ports & ranges are used in this service:

* Destination port 80 access to the GitLab VMs from the PCF Router
* Destination port 22 access to the GitLab VMs from outside of the PCF Network
* Destination port 2222 for SSH access to the `gitlab-ee` VM
* Outbound port 2049 for access to an external NFS Server

## Feedback

Please provide any bugs, feature requests, or questions to [the Pivotal Cloud Foundry&reg; Feedback list](mailto:pivotal-cf-feedback@pivotal.io).

## Further Reading

* [Official GitLab Documentation](http://doc.gitlab.com/ee/)
