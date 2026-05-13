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
