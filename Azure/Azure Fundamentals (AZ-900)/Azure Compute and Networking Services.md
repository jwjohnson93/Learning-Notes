# Azure Compute and Networking Services

## Containers

- Isolated virtual environment
- operating system, application, necessary modules, database, web server, etc.

## Compute Types

- Virtual machines
- Azure Container Instances
- Azure Functions
  - microservices, event driven

## VM Options

- Windows and Linux
- guest on a host computer in Azure datacenter
- stopping a VM deallocates it
- availability sets
  - Fault domains
  - update domains
- Virtual machine scale sets (VMSS)
  - Scale virtual machines
  - specify the OS and how many in the scale set
  - scaled using auto-scale
  - deployed in availability sets
- Azure Virtual Desktop
  - desktop virtualization
  - users get their own profile

## Resources required for a Virtual Machine

- Virtual network
- IP Address
- Network security group
- Network interface
- Disk

## Application Hosting Options

- Azure App Services
  - PaaS service to host apps in the cloud
  - App Service Plan
    - Determines the tier of service
- Azure Kubernetes Service (AKS)
  - Kubernetes in the cloud
  - runs in Kubernetes cluster
    - primary computer - control plane
    - kubernets nodes
  - control plane orchestrates the cluster
  - only pay for the compute
- Applications on Virtual Machines
  - Most flexible, but you have to control and pay for everything

# Virtual Networking

- Azure Virtual Networks
  - full network topology in the cloud
- Virtual Network Peering
  - connect two Vnets together
  - travels across Microsoft's network
- Azure DNS
  - manage DNS records in Azure
  - Internet facing zones - public zones
  - internal facing - private zones
- Azure VPN Gateway
  - secure connection between Azure Vnets and other networks
  - uses a gateway subnet that runs two or more VMs
  - Three types:
    - vnet to vnet
    - site to site
    - point to site
- Azure Express Route
  - connect Azure resources to on-prem networks
  - up to 10Gbps
  - uses dedicated fiber
  - connect directly using Microsoft Enterprise Edge Router

# Public and Private Endpoints

- Public endpoint
  - reachable over the internet
- Private endpoint
  - reachable only over a private network