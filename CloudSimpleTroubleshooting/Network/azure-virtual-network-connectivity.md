# Troubleshooting Azure virtual network connection 

## **Recommended steps**

1. Check that the Virtual Network Gateway that links to your Azure virtual network to CloudSimple is of type **ExpressRoute**. <br>
2. Check if a gateway subnet created in the virtual network. 
3. Check if ExpressRoute Gateway already connected to another ExpressRoute circuit in the same peering location. <br>
4. Check that the correct connection type selected. <br> 
5. Check that the virtual network in the same location as the Virtual Network Gateway. <br> 
6. Check if there is a subnet overlap with the private cloud. <br>
7. Check if the subnet overlaps with another peered virtual network. <br>
8. Check if you are linking more than 10 virtual networks in a standard ExpressRoute Circuit?" <br>

## **Recommended documents**

[Azure Virtual Network Connection using ExpressRoute](https://docs.cloudsimple.com/solutionguides/azure-er-connection/)<br>