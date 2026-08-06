# 💻 Deploying the Windows Server Virtual Machine

---

# 📖 Objective

The objective of this phase was to deploy a Windows Server 2022 virtual machine into Microsoft Azure. This server serves as the primary Windows server for the Azure Administration Lab and demonstrates the deployment of Infrastructure as a Service (IaaS) resources.

---

# 🛠️ Technologies Used

- Microsoft Azure
- Azure Virtual Machines
- Windows Server 2022
- Azure Virtual Network
- Network Security Group
- Public IP Address

---

# Configuration

| Setting | Value |
|---------|-------|
| Resource Group | rg-windows-soc-lab |
| Virtual Machine | vm-dc01 |
| Operating System | Windows Server 2022 Datacenter Azure Edition |
| Region | East US |
| Virtual Network | vnet-windows-soc |
| Network Security Group | nsg-windows-soc |
| Public IP | vm-dc01-ip |
| Administrator | azureadmin |

---

# Review Before Deployment

Before creating the virtual machine, I verified all deployment settings to ensure the resource group, networking, operating system, and security configurations were correct.

### Deployment Summary

![VM Review Summary](../screenshots/virtual-machines/vm-dc01-review-summary.png)

### Networking Configuration

![VM Networking](../screenshots/virtual-machines/vm-dc01-review-networking.png)

### Storage Configuration

![VM Storage](../screenshots/virtual-machines/vm-dc01-review-storage.png)

---

# Deployment

The virtual machine deployment completed successfully within the **rg-windows-soc-lab** resource group.

![VM Deployment Complete](../screenshots/virtual-machines/vm-dc01-deployment-complete.png)

---

# Why This Matters

Azure Virtual Machines provide Infrastructure as a Service (IaaS), allowing organizations to deploy Windows or Linux servers without purchasing physical hardware.

Deploying a Windows Server virtual machine demonstrates cloud administration skills including server provisioning, networking, identity management, and infrastructure deployment.

---

# Skills Demonstrated

- Azure Administration
- Azure Virtual Machines
- Infrastructure as a Service (IaaS)
- Windows Server Administration
- Cloud Networking
- Azure Resource Management

---

# Lessons Learned

Deploying a Windows Server virtual machine in Azure demonstrated how cloud infrastructure differs from traditional on-premises deployments. Throughout this phase, I learned how Azure resources work together, including Resource Groups, Virtual Networks, Network Security Groups, Public IP addresses, and virtual machines.

I also learned the importance of validating deployment settings before provisioning resources and how Azure regional availability can affect virtual machine size selection.
