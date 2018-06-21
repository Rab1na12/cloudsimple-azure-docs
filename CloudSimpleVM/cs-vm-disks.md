Open the Disks page for a selected VM to manage disk assignments.

## Add a Disk
1. On the Disks page, click **Add disk**.

2. Configure each of the following settings by entering or selecting an inline option.

    | Item | Description | 
    | ------------ | ------------- | 
    | Name | Enter a name to identify the disk.  | 
    | Size | Select one of the available sizes.  | 
    | SCSI Controller | Select a SCSI controller. The available controllers vary for the different supported operating systems.  |
    | Mode | Determines how the disk participates in snapshots. Choose one of these options: <br> - Independent persistent: All data written to the disk is written permanently.<br> - Independent, non persistent: Changes written to the disk are discarded when you power off or reset the virtual machine.  This mode allows you to always restart the VM in the same state. For more information, see the [VMware documentation](https://pubs.vmware.com/vsphere-51/index.jsp?topic=%2Fcom.vmware.vsphere.vm_admin.doc%2FGUID-CE98BEB7-B8D5-495B-B9CE-622A4B93AFC6.html). |

3. Click **Save**.

## Delete a Disk
On the Disks page, select the disk and click **Delete**.
