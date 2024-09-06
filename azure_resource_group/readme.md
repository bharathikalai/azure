### azure zero to hero 1st video (topic resource group)
# Azure Resource Group

## Overview

An **Azure Resource Group** is a container that holds related resources for an Azure solution. It includes all the resources you want to manage as a group, such as virtual machines, databases, virtual networks, and storage accounts. Resource groups allow for efficient management and organization of your Azure resources.

## Key Features

- **Logical grouping**: Resources that share the same lifecycle can be grouped together, making it easier to manage.
- **Access control**: Role-based access control (RBAC) can be applied at the resource group level to control access to all resources within the group.
- **Cost management**: Resources in a group can be tagged, enabling better cost tracking and allocation.
- **Dependency management**: Resource groups allow you to deploy and manage resources together that have dependencies on each other.
- **Location specification**: The resource group itself is assigned to a specific Azure region, though resources within the group can span multiple regions.

## Common Use Cases

1. **Managing a collection of related resources**: For example, all the resources for a web application such as the front-end, back-end, and database can be grouped into a single resource group.
2. **Consistent deployment**: Resource groups enable consistent deployment of all resources together via templates (e.g., ARM or Bicep templates).
3. **Simplified monitoring and reporting**: A resource group allows for consolidated monitoring and logging of all resources inside it.

## Creating a Resource Group

You can create a resource group using the Azure portal, Azure CLI, or an Azure template.


