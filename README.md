# Azure Linux VM Templates

Welcome to the Azure Linux VM Templates repository! This project provides Azure Resource Manager (ARM) templates for deploying Linux virtual machines on Microsoft Azure. Whether you're running Ubuntu, CentOS, Debian, or other popular Linux distributions, you'll find templates tailored for easy deployment.

NOTE: This project is a work in progress, or WIP, so content will be added over time. 

## Quick Start

To deploy a VM using these templates, follow these steps:

1. Choose the branch for your desired Linux distribution.
2. Open the `basic-azure-linux-deploy.json` file and modify parameters as needed.
3. Customize parameters if needed (e.g., VM size, username, and password).
4. Deploy the template to Azure using [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/group/deployment?view=azure-cli-latest) or [Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/new-azureps-module-az?view=azps-10.15.0).

## Branches

- `master`: Generic ARM template for common Linux configurations.
- `ubuntu`: ARM templates for deploying Ubuntu VMs.
- `centos`: ARM templates for deploying CentOS VMs.
- `debian`: ARM templates for deploying Debian VMs.

## Contributing

Contributions are welcome! If you have improvements or templates for additional Linux distributions, feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
