# Azure Linux VM Templates

This repository contains Azure Resource Manager (ARM) templates for deploying Linux virtual machines on Microsoft Azure. Each branch corresponds to a different Linux distribution.

## Quick Start

To deploy a VM using these templates, follow these steps:

1. Choose the branch for your desired Linux distribution.
2. Open the `azuredeploy.json` file and modify parameters as needed.
3. Deploy the template to Azure using [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/group/deployment?view=azure-cli-latest) or [Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/new-azureps-module-az?view=azps-10.15.0).

## Branches

- `master`: Generic ARM template for common Linux configurations.
- `ubuntu`: ARM templates for deploying Ubuntu VMs.
- `centos`: ARM templates for deploying CentOS VMs.
- `debian`: ARM templates for deploying Debian VMs.
- ...

## Contributing

Contributions are welcome! If you have improvements or templates for additional Linux distributions, feel free to create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
