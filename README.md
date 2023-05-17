# CMU_Network-Design

*Spring 2023, Network and Internet Security class*

[**Final Report**](https://github.com/haein001/CMU_Network-Design/blob/5fa6bc06c03671655f55cdab48f99628a6f9510d/NIS%20Final%20Project%20Deliverable.pdf)
Final Report for new design of the network


## **Existing diagram of the network**
![image](https://github.com/haein001/CMU_Network-Design/assets/77334059/0722a2fd-cba8-4412-a612-139a44a8880b)

## **New Updated Diagram of the Network**
![image](https://github.com/haein001/CMU_Network-Design/assets/77334059/63fecd3b-8110-4d98-baf2-d3aa333727ff)

### **Challenges with the Design**

- A lack of network border security. Configuring a firewall and adding effective rules
  
- Internal IP addresses are routable. Need for RFC 1918 IP address configuration
  
- A lack of network and VLAN segregation
	
- No security devices within the internal network
	
- Internal servers, AD/DNS/DHCP services are routable
	
- No visible wireless infrastructure
	
- Using FTP instead of SFTP

### **Changes**
**For more details, see [**Final Report**](https://github.com/haein001/CMU_Network-Design/blob/5fa6bc06c03671655f55cdab48f99628a6f9510d/NIS%20Final%20Project%20Deliverable.pdf).**
- VLAN Segmentation
- IP addressing
- Nat Rules/ DHCP
- Firewall Rules
- Purchase new devices within the budget
	- firewall
	- layer 3switch
	- wirellss access points/wireless controller
	- intrustion prevention system
	- warranty/service aggreements/licenses
