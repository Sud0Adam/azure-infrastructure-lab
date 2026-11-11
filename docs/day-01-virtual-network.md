# Day 1 — Azure Virtual Network Deployment

## Objective
Deploy a Microsoft Azure Virtual Network to establish the networking foundation for a cloud infrastructure lab.

## Environment
- **Cloud Provider:** Microsoft Azure
- **Subscription:** Azure Free Trial
- **Resource Group:** `rg-careerlab-dev`
- **Region:** East US 2
- **Virtual Network:** `vnet-careerlab`
- **VNet Address Space:** `10.10.0.0/16`
- **Subnet:** `snet-web`
- **Subnet Address Range:** `10.10.1.0/24`

## Implementation
1. Navigated to Virtual Networks in the Azure Portal.
2. Created a virtual network named `vnet-careerlab`.
3. Selected the existing resource group `rg-careerlab-dev`.
4. Configured the IPv4 address space as `10.10.0.0/16`.
5. Created a subnet named `snet-web` using `10.10.1.0/24`.
6. Left optional paid networking services disabled.
7. Reviewed and deployed the virtual network.

## Verification
Confirmed the following in Azure:
- Virtual Network successfully deployed.
- Correct resource group and region.
- Address space configured as `10.10.0.0/16`.
- One subnet created.

## Technical Concepts
**Virtual Network (VNet):** Provides a private network environment for Azure resources.

**Subnet:** Divides a larger network into smaller IP address ranges.

**CIDR:** Defines the size of an IP address range using prefix notation.

## Next Steps
- Create a Network Security Group (NSG).
- Associate the NSG with `snet-web`.
- Configure and verify network security rules.
- Deploy a Linux virtual machine.
