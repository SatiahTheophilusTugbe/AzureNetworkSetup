# AZURE VIRTUAL NETWORK SETUP/CONFIGURATION
# Project Overview
In this project, I took on the challenge of setting up a cloud network infrastructure using Microsoft Azure. The goal was to create a foundational environment where SatiahCorp could securely deploy, manage, and scale their cloud resources. This involved creating a resource group and a virtual network (VNet) to support various services and applications that would be developed later.

# Detailed Steps
## Creating the Resource Group

The first step in this project was to establish a resource group in Azure, which serves as a container for all related resources. I accessed the Azure portal and searched for "resource" to find the resource group options. By clicking on + Add or Create resource group, I initiated the setup.

![RG1](https://github.com/user-attachments/assets/c2ce652e-8a11-4564-842b-5aba565d727b)

## Key Decisions:
- Naming: I chose a descriptive name for the resource group to ensure clarity when managing multiple resources: (SatiahCorpRG)
- Region Selection: I carefully selected the region based on the class walkthrough, ensuring that all subsequent resources would be created in this same region.

This decision was crucial for minimizing latency and maximizing availability, particularly      important for any time-sensitive or mission-critical applications SatiahCorp might deploy: (Canada) Canada Central

![RG2](https://github.com/user-attachments/assets/1b8ed564-57e9-4b57-b617-affd83d147e5)

Once the resource group was created, I confirmed its setup by navigating to it through the Azure portal.

![RG3](https://github.com/user-attachments/assets/e70add16-606b-4abf-83db-7bfb98770703)

## Setting Up the Virtual Network (VNet)
With the resource group in place, the next task was to create a virtual network (VNet). This network would act as the backbone for all cloud services, allowing for secure communication between various resources.

![VirNet1](https://github.com/user-attachments/assets/5a60e0d3-8287-46c4-b108-3c793ea8e2fc)

## Configuration Steps:
- Network Settings: I used Azure’s default IP address settings, ensuring that the network had enough capacity to support both current and future SatiahCorp operations.
- Security Settings: While setting up the VNet, I opted not to enable DDoS Protection Standard to avoid unnecessary costs, considering that the focus was on building a robust yet cost-effective infrastructure.
- Region Alignment: I ensured that the VNet was configured in the same region as the resource group, maintaining consistency across the setup for optimal performance.

![VirNet2](https://github.com/user-attachments/assets/5ade8c3a-38a2-4e9f-a878-9e0d259d6852)

After finalizing the network settings, I clicked on Create to deploy the VNet. This step marked the successful creation of a foundational network environment ready for further development.

![VirNet3](https://github.com/user-attachments/assets/97c5fce0-4794-4101-85b2-aef1ce7f4b80)

## Final Verification and Next Steps
After setting up the VNet, I revisited the resource group to verify that the VNet was listed as a resource. This confirmed that everything was correctly configured and ready for the next phase of the project. With the resource group and VNet in place, I now have a scalable and secure environment for deploying additional cloud infrastructure, such as virtual machines, databases, and more.

## Technologies
- Azure Virtual Network(VNet)
- Azure Virtual Machines(Windows and Linux OS VM)
- Network Security Group(NSG)
- Remote Desktop Protocol(RDP) for Windows Remote access control
- Command Line Interface/SecureShell(SSH) for Linux Remote Server Management

## Conclusion
This project was a vital step in setting up a cloud environment using Microsoft Azure. By creating a well-structured resource group and VNet, I laid the groundwork for a secure, scalable, and efficient cloud infrastructure. The decisions made during this process, especially regarding region selection and security settings, will ensure that SatiahCorp's resources are both accessible and protected as the project evolves.
