# Microsoft Azure Project

Team Members- 
1. Samiksha Sanjay Desai
2. Pratiksha Suresh Wankhade
3. Prisha RajeshKumar Pandey

   
Project Title:
Doctor Appointment Application’s Virtual Networking Through Azure
Administration.

Problem Statement:
In order to facilitate doctor appointment application, the project aims to provide
peering and a Virtual Private Network (VPN) connection between two virtual networks
that are globally located in different regions. 

Project Description:
  This Project includes Various Azure instances and Services, Azure Virtual Networks,
Azure Virtual Machines, Azure Portal, Azure VPN Gateway, Availability Zones,
Windows and Linux images, Storage Account etc.
  In two different locations, two virtual networks have been created.Subnets were
subsequently established in each virtual network. Then, each subnet has two virtual
machines created in it. A website is Hosted in each Virtual Machine. One gateway
subnet is added to these virtual networks, and two virtual network gateways are then
created in designated areas. Subsequently these virtual networks connected
Bidirectionally with one another and established a VPN tunnel, So that it ensures the
Application’s traffic is private and remains on the Microsoft backbone. It will help in
establishing healthy communication between two different regional networks of this
Application.

Azure Services - 

1. Deployment of Virtual Machines and Hosting a Websites in it

2. V.net to V.net Peering.

3. Virtual Private Network Gateway Connection Bidirectionally.

4. Creation of Storage Account and assigning to specific V.nets

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/bcf77c3f-d441-4b1e-a3d5-29cc989bc5ff)   


Project Synopsis -   
https://drive.google.com/file/d/1YdzmZzUQDv2t8xFaZivjWV9auQNtGLgP/view?usp=sharing      

Project Demonstration Video - 
https://drive.google.com/file/d/17_KwO3suEb4lAFWHhkDXMTBLqR6V1aJ-/view?usp=sharing        


Microsoft Azure Project Synopsis - 
[Microsoft Azure Project - Synopsis.pdf](https://github.com/pratikshawankhade11/azure-project-repo/files/13319612/Microsoft.Azure.Project.-.Synopsis.pdf)


Screenshots and Procedure of Project - 

Step 1 : Creating first Virtual Machine - named ‘Web-Server-A’

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/e5a1f896-7576-41ff-8729-c00785f166e5) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5df9810a-7866-44d8-b1d0-07a45d3c76a4) 

Assigning Network and Subnetwork to the VM

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/fcfac1ac-b8d2-46c2-8784-2e9db091f2b8) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/f480560d-b1da-4fdb-bacc-9d75f97ed8b2) 

Adding Tags

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6f2acb16-1341-482e-b7cf-363fe740c4a0) 

Validation Passed 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/3fa40ba1-360f-460b-a41d-d22b110ab4e7) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/cf5f90b4-a98f-406d-9d31-84931b5c6b60)

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/15b53c99-e132-42e7-ba4f-5a87ad5c0c8b)

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/346211a4-9878-4f58-ac11-fb69ebf38793)

Deployment is in Process 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/bcdea0b2-4095-4454-a78e-eb32ce533dc5)  

Here Deployment of our first Virtual Machine is Completed

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c994df28-802d-4caa-a747-69f2b59a0044) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/cd813ac0-ea2d-4ac2-942d-44af6ec88fa3) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5f32b415-2f06-4c01-be5d-77a4a07a327c) 

Download the RDP Connecting to the Remote Desktop of our first VM 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/d4fc5fed-300f-48ef-8dd6-6cfea648fee0) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6447487e-4875-44d6-a37a-30f6b2feafda) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/63b1325d-cc50-4c12-b07b-1a051f126b3b) 

Here we are putting Username and Password to connect 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/b999e4c2-1e26-4a4e-a132-7ceaeb92668b) 

This is our Windows Desktop of first VM 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/7184e45d-f86f-4dfc-bc15-86b20ef298a1) 

Server Manager of this Virtual Computer 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/e51f74cf-1732-4f65-a447-80b869d97057) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/52463e27-4b28-4f57-9926-15653a3baf6d) 

Adding Server Roles 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/7581532e-9f5e-40bd-a2a2-f654e52145f0) 

Installing Web Server (IIS)

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/0c0e65e3-7fe7-4407-91c3-45019191c255) 

Adding required files in the root directory 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8d4c29a7-e30a-4ad1-a1c8-799a112187ce) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/1bc15047-1782-4d06-8ade-e5aa49eeae08) 

In this way we have hosted a website through Web Server (IIS) Step 2 : Creating Second Virtual Machine - Web-Server-B 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5bc91881-c987-496e-936c-c35faaee268a) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/a7e2494f-94c7-402a-a1c7-fb5a9f9f86d1) 

Assigning Same Virtual Network to the same regional vm’s 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/75faa577-5e32-42d8-b187-df7240d70691) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5aa83644-7c1a-40c8-9a1f-7e8e163cae64) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8238d600-c538-4012-933b-61acd92c5baf) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/905cce8c-49af-4ff4-b4f1-942b73ccc4cc) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/4bcd613a-0492-4dbd-867d-0764ceb2231f) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/b180d8d1-e1e0-48fc-b8a0-fed83d174929) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/77d821c3-747d-4b62-8d10-a4b63d40a905) 

Here Deployment is Completed of our Second VM 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/3dc9a5d6-7ac0-4a6b-be6e-e964d44a112a) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6282c489-7ec6-4f3e-885b-2a632c91000a) 

Step 3 : Creating Third Virtual Machine - Web-Server-C 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/e17a60ac-04c9-4cfc-830e-69ccda041238) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/44b412c3-0a76-434d-8d28-7b4a250c1c46) 

Assigning New Virtual Network of ip Address - 192.168.0.0/16 and Subnet - 192.168.0.0/24

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/73db1754-30dd-42d1-bd83-e0270b935829) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c3580a8d-07b4-473d-a091-4f5b797326d4) 

Adding Tags 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/a7a7e4b1-a713-45b9-8f6a-3ce4fe172821) 

Validation Passed 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/aae3f475-51fc-497b-9bbb-b151c0406ae3) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/0eef8b6e-058e-4c82-aad6-bf4938b4e046) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/fe0218c5-9006-44b9-ad97-9c39823b1ecc) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/07106547-93ec-4b30-9af2-2f06d50052b4) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/ff4014ad-4df5-44ca-b502-206d7f0c8f20) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/a0e17b1e-c87e-449d-84d4-81cb1cae4bed) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/ce8ed9c6-985a-41c8-86b3-9ec4b52b56bd) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/49cb9a4e-69ba-4d34-9ad0-cd8882ed0448) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8fed52da-762f-46a6-b652-31a74a0038e9) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/36b42a23-7f4d-48a9-80ca-e5e1e847a027) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/1800b1ac-5bec-46a0-bd3c-9a724cddbaf1) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/0282cd28-123d-4d0e-8d4c-14ba64af55ff) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/61286859-bf76-49a8-836c-f17c9048ab70) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/7152e790-f2e6-42dd-a120-a5789aa98bf8) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8139c5ee-8044-48c9-9d75-adf484d06f3c) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/95301d7a-c539-4c6b-8777-5e88cbe25cfc) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/99c4b433-3f6a-4204-94b2-39ab078b4e27) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/a57de383-6685-4597-8205-de32dc95e253) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8e886e7d-f700-4fbb-aa0e-8f5120d8eebb) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/8ec02d3b-0fc5-4d2b-a25f-6ee27d5d0aa7) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/a910bcf7-54c9-4b49-b91a-8b553ded7304) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c53b9f6f-4105-49c8-a4d0-06e0a66a507f) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/f7a69a88-2e4d-4cc4-9de6-1a4985668945) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/77321190-66f8-4fa8-87bc-eb76c54023b1) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/46c4b4b7-b7d4-43f7-9c0d-c5fdd119dae3)  

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/13400e45-83a1-4062-93cc-7902532a9fda) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/86627070-3261-4762-a134-b7bdf0dfa61b) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6bd32f0e-388f-4df4-9a11-c6947688536e) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c3342a85-29cb-420f-b156-fd8b249fb63b) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/1760926a-8d77-4bd7-b577-620d0ec2dfd8) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/64987b06-a598-45e7-a41a-7fd77ec00237)

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/db45930e-f8e7-4bde-9a55-0dc6be8fc901) 

Step 7 : Creating Virtual Private Network Gateway to the Web Server AB in Italy North 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c93565ad-90e6-4bef-86fd-a33ecea56aac) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/79701a6d-b1ce-4c57-b511-097401988480) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/7b877670-092b-4f59-93dd-7e29f26ab7ae) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/cd1dd420-11de-41ee-895b-b5aeb9105c9d) 

Creating Virtual Private Network Gateway to the Web Server CD in Germany West Central 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/2aecc5df-4c2c-477e-abdc-fcde2fabf32e) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5f98a7d5-064d-43f0-8009-37ca1daff890) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/f1390348-9671-49a7-ab35-5604745e81cf) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/f0879a86-61dc-4d3d-a9b0-20211b7708cb) 

Here We Have Created Virtual Private Network Gateways for Both Networks 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/219880fe-a75f-414e-9ec2-f9f47a5525a9) 

Step 8 : Then We are Connecting Virtual Private Network Gateway of Web Server CD and Virtual Private Network Gateway of Web Server AB Bidirectionally 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/5f2c00b5-3b79-45ca-b099-20888f1d06fc) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/19738a00-b009-4387-b2e6-61303e23cd9b) 

Adding Tags to the Connection 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/e8c43486-d417-4570-902c-7ff69eb411c6) 

Here Validation is Passed for the Connection 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/85df7746-9f04-4f87-9a92-6790355accbe) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/4e9f5dd0-65aa-443a-b78e-6a03b034e5f5) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/b672193b-597b-42b0-a589-c79f352dd651) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/fefb02e3-eae3-4609-b1d7-3bc5ba28b682) 

In this way We Have Connected Virtual Private Network Gateway of Web Server CD and Virtual Private Network Gateway of Web Server AB Bidirectionally. 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/9686faac-5bd9-4d6c-b6ad-f453c7fb04cd) 

Virtual Network Connections Diagram :

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/4a4edd60-aa78-475a-9346-b034e7be9d48) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/b3253724-4ac9-4980-9624-37b905f2dd90) 

Step 9 : Creating a Storage account in the Central India which will be only accessible to
Network of Web Server AB

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6a1bd6b2-d6f7-4bf2-9c1d-e7b2ccd56b5b) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6869861f-39ba-4ec9-90c0-2a53dcd790a9) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/dab36096-8fec-4b3d-a1cb-60495fafdd24) 

Creating a Storage account in the Germany West Central which will be only accessible to Network of Web Server CD 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/6daea82d-55b8-4767-9905-69d26e74e90a) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/27bbe71f-3526-4dd0-9f60-978db18bb72d) 

Adding a file in container of Storage Account 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/c7b5490f-2fec-43de-8c82-a9747b4169a8) 

![image](https://github.com/pratikshawankhade11/azure-project-repo/assets/90560074/4337dd81-5c22-4769-9aa0-9d839f729d58) 

                                        ______________ Thank You _____________
