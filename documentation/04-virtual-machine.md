# 💻 Deploying a Windows Server Virtual Machine

---

# 📖 Objective

The objective of this phase was to deploy a Windows Server 2022 virtual machine in Microsoft Azure. This virtual machine serves as the primary server for the Azure Administration Lab and demonstrates the deployment and management of Infrastructure as a Service (IaaS) resources within a cloud environment.

---

# 🛠️ Technologies Used

- Microsoft Azure
- Azure Virtual Machines
- Windows Server 2022 Datacenter: Azure Edition
- Azure Resource Groups
- Azure Virtual Network
- Azure Network Security Group (NSG)
- Azure Public IP Address
- Azure Portal

---

# ⚙️ Configuration

| Setting | Value |
|---------|-------|
| Resource Group | rg-windows-soc-lab |
| Virtual Machine | vm-dc01 |
| Operating System | Windows Server 2022 Datacenter: Azure Edition |
| Region | East US |
| Virtual Network | vnet-windows-soc |
| Network Security Group | nsg-windows-soc |
| Public IP | vm-dc01-ip |
| Administrator Account | azureadmin |

---

# 📋 Deployment Review

Before deploying the virtual machine, I carefully reviewed all configuration settings to ensure the deployment aligned with the network architecture and security configuration created during the previous phases of the lab.

The review included verifying the resource group, operating system, virtual network, network security group, administrator account, and virtual machine specifications before provisioning the server.

![VM Review Summary](../screenshots/virtual-machines/vm-dc01-review-summary.png)

---

# 🌐 Networking and Storage Configuration

The networking and storage configuration was reviewed prior to deployment. The virtual machine was connected to the existing Virtual Network, secured with the previously created Network Security Group, and configured with the default operating system disk settings appropriate for this Azure Administration Lab.

![VM Networking and Storage](../screenshots/virtual-machines/vm-dc01-review-networking-&-storage.png)

---

# ✅ Deployment Completed Successfully

After validating all deployment settings, Azure successfully provisioned the Windows Server 2022 virtual machine.

The deployment automatically created and configured the required Azure resources, including:

- Virtual Machine
- Network Interface Card (NIC)
- Operating System Disk
- Public IP Address
- Virtual Network Connection
- Network Security Group Association

This deployment demonstrates the provisioning of Infrastructure as a Service (IaaS) resources within Microsoft Azure.

![VM Deployment Complete](../screenshots/virtual-machines/vm-dc01-deployment-complete.png)

---

# ✔️ Verification

The deployment was verified by confirming:

- The deployment completed successfully.
- The virtual machine appeared within the Resource Group.
- The Network Security Group was successfully associated with the virtual machine.
- The Public IP Address was assigned.
- The virtual machine status showed **Running** within the Azure Portal.

---

# ☁️ Why This Matters

Azure Virtual Machines provide organizations with scalable Infrastructure as a Service (IaaS), allowing Windows and Linux servers to be deployed without purchasing or maintaining physical hardware.

Deploying a Windows Server virtual machine demonstrates foundational cloud administration skills including infrastructure deployment, networking, server administration, and Azure resource management.

---

# 🎯 Skills Demonstrated

- Microsoft Azure Administration
- Azure Virtual Machines
- Infrastructure as a Service (IaaS)
- Windows Server Administration
- Azure Networking
- Network Security Groups (NSGs)
- Public IP Configuration
- Azure Resource Management
- Cloud Infrastructure Deployment
- Technical Documentation using GitHub

---

# 📚 Lessons Learned

Deploying a Windows Server virtual machine provided valuable hands-on experience with Microsoft Azure infrastructure.

Throughout this phase, I learned how multiple Azure resources work together to successfully deploy a virtual machine, including Resource Groups, Virtual Networks, Public IP Addresses, Network Security Groups, and Virtual Machines.

During deployment, I also encountered Azure resource availability limitations that prevented the originally selected virtual machine size from being used within the chosen region. After troubleshooting the issue, I identified an available virtual machine size and successfully completed the deployment.

Working through this challenge reinforced the importance of troubleshooting, adapting to cloud resource availability, validating deployment settings before provisioning resources, and understanding how Azure regional capacity can affect infrastructure deployments.

This experience strengthened both my Azure administration skills and my confidence troubleshooting cloud infrastructure in a real-world environment.
