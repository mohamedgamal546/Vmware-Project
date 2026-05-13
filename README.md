# 🖥️ VMware vSphere Full Lab Project

## 📌 Overview

This project demonstrates the design and implementation of a complete **VMware vSphere lab environment** using nested virtualization.

The goal was to build a real-world enterprise-like infrastructure including:
- ESXi hosts
- vCenter Server
- Cluster configuration
- High Availability (HA)
- Distributed Resource Scheduler (DRS)
- vMotion
- Fault Tolerance (FT)
- Shared storage (NFS)
- Content Library
- VM lifecycle operations (clone, snapshot, templates)

---

## 🏗️ Technologies Used

- VMware Workstation (Nested Virtualization)
- VMware ESXi
- VMware vCenter Server Appliance (VCSA)
- NFS Storage
- Linux (Ansible Server VM)
- Git & GitHub for documentation

---

## 🧱 Lab Architecture

The environment consists of:

- 1 vCenter Server Appliance
- 2 ESXi Hosts running as virtual machines
- Shared NFS Datastore
- Management Network + VM Network + Migration Network
## ⚙️ Project Implementation Steps

### 1. ESXi Deployment
- Installed two ESXi hosts on VMware Workstation
- Configured management network and IP addressing

### 2. vCenter Server Setup
- Deployed VMware vCenter Server Appliance (VCSA)
- Added ESXi hosts to vCenter inventory

### 3. Cluster Configuration
- Created a vSphere cluster
- Enabled HA, DRS, and vMotion

### 4. Networking Configuration
- Configured virtual switches and port groups:
  - Management Network
  - VM Network
  - vMotion Network

### 5. Storage Configuration
- Configured NFS shared datastore
- Mounted storage on both ESXi hosts

### 6. VM Operations
- Created and managed virtual machines
- Performed:
  - Cloning
  - Snapshots
  - Template creation
  - vMotion migration

### 7. High Availability Testing
- Simulated ESXi host failure
- Verified automatic VM failover

### 8. Fault Tolerance
- Enabled FT for critical VM
- Verified continuous availability


## 📸 Screenshots & Evidence

All steps were documented with screenshots including:

- ESXi installation process
- vCenter configuration
- Cluster setup
- vMotion migration
- HA failover test
- FT activation
- VM lifecycle operations


## 🚀 Project Outcome

This project demonstrates a real-world enterprise vSphere environment with:

✔ High availability (HA) implementation  
✔ Load balancing using DRS  
✔ Live migration using vMotion  
✔ Fault tolerance for critical workloads  
✔ Centralized management using vCenter  
✔ Shared storage using NFS  
✔ Full VM lifecycle management  

This project simulates production-level virtualization infrastructure used in modern data centers.


## 👨‍💻 Author

Mohamed Gamal Nasser  
Cloud & DevOps Enthusiast  
