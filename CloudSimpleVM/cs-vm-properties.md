---
author: Barbara
date: May 24, 2018
---

The Properties page displays status and other information about the VM.

![Azure Portal Overview page](images/azp-properties.png)
 
 This page contains the following information. Some of this informaton is also presented on the [Overview page](azureoverviewpage.md).

| Item | Description | 
| ------------ | ------------- | 
| Resource Group | Deployment group to which this VM belongs.  | 
| Status | Operational status of the VM.  | 
| Location | Azure region in which this VM is hosted.  | 
| Subscription or<br>Subscription Name | Azure subscription associated with your Private Cloud deployment. | 
| Subscription ID | ID of the Azure subscription.  | 
| Resource Pool | Resource pool in the CloudSimple VMware vSphere cluster that this VM belongs to.  | 
| Computer Name | Name of the CloudSimple VM.  | 
| Operating System | Operating system for the VM as reported in vSphere. For a list of supported operating systems, see [Supported host operating systems for VMware vCenter Server installation](https://kb.vmware.com/s/article/2091273). | 
| Size |  Compute and memory resources assigned to the VM in vSphere.  | 
| Public IP address/DNS name | Public IP address that is mapped to the local IP address of the VM in the CloudSImple Public IP service. See [Public IPs](../csportal/publicips.md).  | 
| IP Addresses | IP addresses reported for the VM guest by VMware Tools.  | 
| vSphere Networks | Networks assigned to the NICs in vSphere. | 
| VMware Tools | VMware Tools version, if installed.  | 
