# Hybrid-Connectivity-and-Disaster-Recovery-DR-
Project Goal: Design, implement, and secure a hybrid cloud environment for a small/medium business, including backup and disaster recovery.

# Key Tasks & Azure Services:

Networking: Create an Azure VNet, multiple subnets (e.g., Web, App, DB). Configure VNet Peering to connect two VNets in different regions (simulating production and DR).

Compute: Deploy a couple of Windows/Linux Azure Virtual Machines (VMs). Secure access using Azure Bastion instead of RDP/SSH directly to the public internet.

Security: Implement Network Security Groups (NSGs) to control traffic between subnets.

Storage: Set up an Azure Storage Account with different access tiers and lifecycle management policies.

Data Protection: Configure Azure Backup for the VMs and Azure Site Recovery to replicate a VM to the secondary (DR) region.
