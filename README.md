# pyVMC
Welcome to PyVMC !

## What is PyVMC ? 
PyVMC is a Python tool developed for VMware Cloud on AWS. PyVMC was created by Nicolas Vibert and Matt Dreyer.

## What are the pre-requisites for PyVMC ?
- Python3 installed on your machine
- a VMware Cloud on AWS account

## How do I use PyVMC ?
- Download the PyVMC.py file and the config.ini file. 
- Edit the config.init with your own SDDC ID,  Organization (Org) ID and your access token.

## Do I need to know Python?
No! You can simply use it to consume and manage your VMware Cloud on AWS SDDC (Software-Defined Data Center). 

## Is it officially supported by VMware?
Sorry but no, this is a community-based effort. Use it at your own risk. It has extensively been tested though and we'll endeavour to fix any bugs.

## Which version of VMware Cloud on AWS has it been tested against?
Versions 1.9 and 1.10. I don't guarantee support with previous versions. 
I will, however, endeavour to verify compatibility as we release new versions.

## What if I find a bug or need a new feature?
Please raise it on GitHub and I will look into it.

## Where can I find documentation about VMware Cloud on AWS:
Please check the online documentation:
https://docs.vmware.com/en/VMware-Cloud-on-AWS/index.html

## Where can I find documentation about each pyVMC commands?
https://nicovibert.com/2020/02/25/pyvmc-python-vmware-cloud-aws/

## Release Notes
v1.0 provides users to:
- Create and remove networks
- Create and remove groups and services
- Create and remove security rules on the Management and Compute Gateways.
- Request, remove and update Public IP addresses.
- Display information about Direct Connect (such as BGP AS, MTU and VPN preference)
- Show VPN statistics, 
- Show DNS Zones and Services
- Create and remove NAT rules
- Display information about SDDC and org users
- Display information about VMs in the SDDC

v1.0 does not support:
- Create/Read/Update/Delete (CRUD) for DHCP Relay 
- Create/Update/Delete (CRUD) for DNS Config.
- Create/Read/Update/Delete (CRUD) for Port Mirroring.
- Create/Read/Update/Delete (CRUD) for IPFIX.
- Create/Read/Update/Delete (CRUD) for non-TCP/UDP based services
- Create/Read/Update/Delete (CRUD) for Distributed Firewall Rules
