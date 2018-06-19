---
author: Barbara
date: May 24, 2018
---

Open the Network Interfaces page for a [selected VM](azuremanagevms.md) to view, add, or delete network interfaces (NICs).

## Add a Network Interface
1. On the Network Interfaces page, click **Add network interface**.

    ![Azure Portal Overview page](images/azurenetworkinterfaces.png)

2. Configure each of the following settings by entering or selected an inline option.

    | Control | Description | 
    | ------------ | ------------- | 
    | Name | Enter a name to identify the interface.  | 
    | Network | Select from the list of configured networks in your Private Cloud vSphere.  | 
    | Adapter | Select a vSphere adaptor from the list of available types configured for the VM. |
    | Power on at Boot | Choose whether to enable the NIC hardware when the VM is booted. The default is **Enable**. |

3. Click **Save**.

<!--
## Enable or Disable a Network Interface
When you create a network interface, it is enabled by default. To change between enabled and disabled, click the interfaces in the list to display the controls...
-->

## Delete a Network Interface
On the Network Interfaces page, select the interface and click = **Delete**.
