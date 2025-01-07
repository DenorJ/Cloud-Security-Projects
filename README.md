# Cloud-Security-Projects
Microsoft Azure Labs Practical's 
Lab 02: Network Security Groups and Application Security Groups Using Microsoft Azure.
![Azure-Labs-Pratice](https://github.com/user-attachments/assets/ede24837-5caa-4dfe-9207-d71c3a4c7e5e)

Step-by-step account of how I carried out this task and its benefits to any organisation:

Step 1: Set Up the Virtual Network I began by creating a virtual network (VNet) in the Azure portal. This VNet would serve as the foundation for our infrastructure, housing all the necessary resources.

Step 2: Create Subnets Following the VNet setup, I created two subnets within it:

One subnet for the Web Servers.

One subnet for the Management Servers.

Step 3: Set Up Application Security Groups (ASGs) Next, I established two Application Security Groups (ASGs):

One ASG for the Web Servers.

One ASG for the Management Servers.

Step 4: Assign Network Interfaces to ASGs I then assigned the network interfaces of the virtual machines (VMs) to their respective ASGs, ensuring clear segregation between the Web Servers and Management Servers.

Step 5: Create Network Security Groups (NSGs) I created a Network Security Group (NSG) for each subnet:

One NSG for the Web Servers subnet.

One NSG for the Management Servers subnet.

Step 6: Define NSG Rules for the Management Servers For the Management Servers NSG, I defined the following rules:

Allow inbound RDP (port 3389) from my IP address or a specified range of IP addresses.

Deny all other inbound traffic.

Step 7: Define NSG Rules for the Web Servers For the Web Servers NSG, I specified these rules:

Allow inbound HTTP (port 80) from any source to display the IIS web page.

Deny inbound RDP (port 3389) to prevent remote desktop access.

Deny all other inbound traffic.

Step 8: Test the Configuration Finally, I tested the configuration by:

Attempting to RDP into the Management Servers to ensure access was possible.

Trying to RDP into the Web Servers to confirm that access was denied.

Accessing the Web Servers through a web browser to verify the IIS web page was displayed.

Benefits to Any Organisation Implementing this setup offers several key benefits to any organisation:

Security: By controlling access using NSGs and ASGs, the organisation can ensure that only authorised personnel can access sensitive servers and services.

Segmentation: The clear division of servers into different groups helps in managing and securing each group independently.

Compliance: Organisations can meet regulatory and compliance requirements by enforcing strict access control policies.

Operational Efficiency: Simplified management of network security rules leads to more efficient operations and troubleshooting.

By following these steps, I successfully implemented the virtual networking infrastructure, ensuring that it met the specified requirements and enhanced the organisation’s security posture.

![Screenshot 2025-01-07 102225](https://github.com/user-attachments/assets/0d0122ff-5702-48cd-9c52-45c70336e24f)
