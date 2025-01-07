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


![Screenshot 2025-01-07 102225](https://github.com/user-attachments/assets/0d0122ff-5702![Screenshot 2025-01-07 104516](https://github.com/user-attachments/assets/cc9d5c6a-f397-4f6e-8778-f52e421fe202)
-48cd-9c52-45c70336e24f)![Screenshot 2025-01-07 105959](https://github.com/user-attachments/assets/81f4ea26-dc33-499f-bcf9-0f616c69292b)

![Screenshot 2025-01-07 105959](https://github.com/user-attachments/assets/27c2a512-2c1![Screenshot 2025-01-07 105234](https://github.com/user-attachments/assets/f990880a-8c20-45e9-902a-1d5a748df361)
9-4cee-999d-5![Screenshot 2025-01-07 104646](https://github.com/user-attachments/assets/963ae425-4692-4934-beb2-e453![Screenshot 2025-01-07 104935](https://github.com/user-attachments/assets/52bc974f-bea5-4767-b7f1-0b8ef58c352f)
0058c9b5)
f08825d53ae)![Screenshot 2025-01-07 104759](https://github.com/user-attachments/assets/f93c1d31-f7ca-46e7-ba9e-612cd7eff27d)


![Screenshot 2025-01-06 231417](https://github.com/user-attachments/a![Screensho![Screenshot 2025-01-07 103109](https://github.com/user-attachments/assets/e76e1f3a-71a7-4983-92ad-9ae156f5947a)
t 2025-01-06 233311](https://github.com/user-attachments/assets/9d0aef40-987b-4201-9786-5417070184ab)
ssets/0bb81686-e991-4ec7-b4bf-d6684c052548)![Screenshot 2025-01-07 000302](https://github.com/user-![Screenshot 2025-01-07 000331](https://github.com/user-attachments/assets/29534ed8-b6fd-4855-bcae-2a4f0ca4b243)
attachments/assets/b82330af-4fac-4368-b34f-6b4d6c4f7b17)

![Screenshot 2025-01-06 233357](https://github.com/user-attachments/assets/65d55821-c59f-458f-9248-7bcca48f6b40)
![Screenshot 2025-01-07 102225](https://github.com/user-attachments/assets/3509b8ae-792f-4d50-80af-53f336a91f4a)

![Screenshot 2025-01-06 231755](https://github.com/user-attachments/assets/0fa13d31-3f98-421f-aff3-75ae5ff95a1f)
![Screenshot 2025-01-06 231939](https://github.com/user-attachments/assets/c1168a53-eb47-47e4-b533-389ae8d6d85d)

![Screenshot 2025-01-06 232146](https://github.com/user-attachments/assets/ae0f9a77-ef61-462d-9c21-9357058faf50)

