# Troubleshooting network connectivity between VMs 

## **Recommended steps**

1. Check if there are firewall rules blocking any outbound traffic. <br>
2. Check the VM network configuration: IP address, subnet mask and gateway. <br>
3. Check if the VM is attached to correct distributed port group. <br>
4. Check if the distributed port group has correct VLAN ID. <br>
5. If you are connection to on-premises VM, check the ExpressRoute connection. <br>

## **Recommended documents**

[Use VLAN Information to Set Up a Distributed Port Group in vSphere](https://docs.cloudsimple.com/csportal/network/vlansubnet/#use-vlan-information-to-set-up-a-distributed-port-group-in-vsphere)<br>
[Firewall Rules](https://docs.cloudsimple.com/csportal/network/firewall/#firewall-rules)<br>
[VLANs/Subnets](https://docs.cloudsimple.com/csportal/network/vlansubnet/)<br>