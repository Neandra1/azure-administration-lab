# 🛡️ Creating a Network Security Group (NSG)

---

# 📖 Objective

The objective of this phase was to create a Network Security Group (NSG) to control inbound and outbound traffic for Azure resources within the lab environment.

Network Security Groups provide an important layer of security by filtering network traffic based on configurable security rules.

---

# 🛠️ Technologies Used

- Microsoft Azure
- Network Security Groups (NSG)
- Azure Networking

---

# Configuration

| Setting | Value |
|---------|-------|
| Resource Group | rg-windows-soc-lab |
| NSG Name | nsg-windows-soc |
| Region | East US |

---

# Why This Matters

Network Security Groups help secure Azure environments by allowing administrators to define which traffic is permitted to reach virtual machines and other resources.

Using NSGs follows the principle of least privilege by allowing only the required network traffic while blocking unnecessary access.

---

# Skills Demonstrated

- Azure Networking
- Network Security
- Cloud Administration
- Infrastructure Security

---

# Verification

The Network Security Group was successfully deployed within the **rg-windows-soc-lab** Resource Group.

*(Insert screenshot: nsg-created.png)*

---

# Lessons Learned

Implementing a Network Security Group demonstrated the importance of applying security controls before deploying workloads into a cloud environment.

Configuring security at the network level helps reduce the attack surface and supports a defense-in-depth strategy.
