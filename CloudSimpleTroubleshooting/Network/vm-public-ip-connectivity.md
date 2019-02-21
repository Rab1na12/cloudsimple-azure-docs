# Troubleshooting network connectivity between VMs 

## **Recommended steps**

1. Check if the virtual machine hosting the application is running. <br>
2. Check if the virtual machine's IP address, subnet mask or gateway configured correctly. <br>
3. If you are using NSX Distributed Firewall in your Private Clouds, check if it blocks access to that virtual machine. <br>
4. Check if the virtual machine's operating system firewall rules block the application's required ports. <br>
5. Check if there are firewall rules blocking any inbound or outbound traffic. <br>
6. Check if the public IP address is mapped to the correct virtual machine. <br>

## **Recommended documents**

[Public IP address](https://docs.cloudsimple.com/csportal/network/publicips/)<br>
[Firewall Rules](https://docs.cloudsimple.com/csportal/network/firewall/#firewall-rules)<br>
[VLANs/Subnets](https://docs.cloudsimple.com/csportal/network/vlansubnet/)