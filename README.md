# VMware vSphere Enterprise Virtualization Project

##  Overview
This project implements a complete VMware vSphere lab environment using three physical servers to simulate an enterprise datacenter. It demonstrates the deployment and management of VMware ESXi, vCenter Server, shared storage, and advanced features such as vMotion, HA, DRS, and Fault Tolerance.

##  Lab Architecture
- **Server 1:** VMware ESXi Host 01
- **Server 2:** VMware ESXi Host 02
- **Server 3:** Windows Server configured as NFS Shared Storage
- **vCenter Server Appliance (VCSA):** Deployed as a virtual machine
- **Cluster:** Centralized management of both ESXi hosts

##  Network Topology
<img width="702" height="468" alt="image" src="https://github.com/user-attachments/assets/bd2891da-e61d-4855-8fed-2ff784db7738" />


##  Features Implemented
- ESXi Installation and Configuration
- vCenter Server Deployment
- Network Segmentation (Management, vMotion, Storage, VM Traffic)
- Shared NFS Datastore
- Content Library
- Virtual Machine Creation
- Templates, Snapshots, and Cloning
- vMotion
- High Availability (HA)
- Distributed Resource Scheduler (DRS)
- Fault Tolerance (FT)

##  Project Objectives
- Build an enterprise virtualization environment
- Configure shared storage and networking
- Deploy and manage virtual machines
- Enable live migration and automatic failover
- Demonstrate workload balancing and continuous availability

##  Technologies Used
- VMware ESXi
- VMware vCenter Server
- Windows Server
- NFS Storage
- VMware vSphere Client

