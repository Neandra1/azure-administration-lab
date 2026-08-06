# 🌐 Creating the Virtual Network

---

# 📖 Objective

The objective of this phase was to establish the foundational network infrastructure for the Azure Administration Lab by creating a Virtual Network (VNet) and subnet.

The Virtual Network provides secure communication between Azure resources and serves as the cloud equivalent of an on-premises enterprise network.

---

# 🛠️ Technologies Used

- Microsoft Azure
- Virtual Network (VNet)
- Subnets
- Azure Resource Groups

---

# Configuration

| Setting | Value |
|---------|-------|
| Resource Group | rg-windows-soc-lab |
| Virtual Network | vnet-windows-soc *(Azure appended a unique suffix during deployment)* |
| Region | East US |
| Address Space | 10.0.0.0/16 |
| Subnet | subnet-servers |
| Subnet Range | 10.0.0.0/24 |

---

# Why This Matters

Virtual Networks allow Azure resources to communicate securely while remaining isolated from other networks.

Creating a dedicated subnet provides logical segmentation, making it easier to organize workloads, apply security controls, and support future growth.

This design mirrors the network segmentation commonly used in enterprise environments.

---

# Skills Demonstrated

- Azure Networking
- Virtual Network Configuration
- Subnet Planning
- Cloud Infrastructure
- Network Design

---

# Verification

The deployment completed successfully and the Virtual Network was created inside the **rg-windows-soc-lab** Resource Group.

*(Insert screenshot: vnet-created.png)*

---

# Lessons Learned

Building a Virtual Network reinforced the importance of planning cloud infrastructure before deploying virtual machines or services.

By creating the network first, future resources can be deployed into a structured and secure environment.
