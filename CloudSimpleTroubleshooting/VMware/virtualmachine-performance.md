# Troubleshooting virtual machine performance 

## **Recommended steps**

1. Check vCenter events for a disconnected or not responsive ESXi host. <br>
2. Check vSAN Health tests for vSAN resync'ing components. <br>
3. Check vSAN Performance stats for for high congestion or I/O that is persistently higher than total disks I/O. <br>
4. Check vSAN storage policy for better configuration. e.g. larger stripe width or a better RAID type. <br>
5. Check network IO Control (NIOC) configuration. <br>
6. Check for I/O overhead due to features in use e.g. vSAN encryption, vSAN Checksum. <br>
7. Ensure that there are no backup activities during peak I/O. <br>
8. Ensure that there are no virtual machine snapshot operation during peak I/O. <br>
9. Check the guest OS file system 4KB alignment. <br>
10. Ensure that Memory Trimming feature is disabled on I/O intensive virtual machines that are not memory intensive. <br>
11. Check for active On-demand virus scan activities in the virtual machine. <br>
12. If using SQL Server, check for optimization tips. <br>
