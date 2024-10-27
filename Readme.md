# AWS VPC Setup Project

## Overview
In this project, I set up a Virtual Private Cloud (VPC) and its associated networking components, configuring a secure and accessible environment for resources hosted in AWS. 

## Steps

### 1. VPC Creation
- Created a **VPC** to establish an isolated network environment, providing control over IP address ranges and routing.

### 2. Subnet Configuration
- Configured a **subnet** within the VPC to manage a segment of the IP range, ensuring resource separation and network organization.
- Enabled **auto-assigned IP addresses** for the subnet, allowing resources to automatically receive IPs, which was an unexpected but essential step.

### 3. Internet Gateway (IGW)
- Created and attached an **internet gateway** to the VPC to enable internet access for resources within the public subnet.

### Key Insight
- The necessity of configuring auto-assigned IP addresses was an unexpected aspect, as I initially assumed default settings would be sufficient for internet connectivity.

## Summary
This setup establishes the **networking tier** in the cloud architecture, forming the foundational network layer for secure resource communication and external connectivity.

---

**Next Steps:** Configure security groups and routing tables to manage traffic and enhance security.
