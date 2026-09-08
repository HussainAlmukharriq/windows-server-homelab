# Lab Setup and Virtualization

## Objective

Build a virtualized Windows Server environment for gaining hands-on experience with Windows administration, networking, and enterprise domain services.

## Hardware

The homelab is hosted on a Beelink SER3 mini PC and connected to my home network through Ethernet.

## Virtualization Platform

I installed Proxmox VE as the virtualization platform for the lab. Proxmox allows multiple virtual machines to operate on the same physical system while maintaining separate operating system environments.

## Virtual Machines

### DC01

- Operating System: Windows Server 2022
- Role: Domain Controller
- Active Directory Domain Services
- DNS Server
- DHCP Server

### WIN11

- Operating System: Windows 11
- Role: Domain-joined client workstation
- Used to test domain authentication, Group Policy, network services, and administrative configurations

## Domain

The Active Directory environment uses the following internal domain:

`bunbun.local`

## What I Learned

Building the environment provided hands-on experience with:

- Installing and managing a Type 1 hypervisor
- Creating and configuring virtual machines
- Installing Windows Server
- Installing Windows client operating systems
- Configuring virtual networking
- Understanding the relationship between servers, clients, and domain services
