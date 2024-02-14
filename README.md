# Project Name

## Overview

This project uses Infrastructure as Code (IaC) to automate the process of setting up and managing infrastructure. It includes two different IaC tools: Bicep and Terraform.

## Structure

- `.github/workflows/`: This directory contains GitHub Actions workflows for deploying infrastructure using Bicep and Terraform.
  - `deployByBicep.yml`: This workflow deploys infrastructure using Bicep.
  - `deployByTerra.yml`: This workflow deploys infrastructure using Terraform.
- `InfrastructureAsCode/`: This directory contains the main IaC files for Bicep and Terraform.
  - `main.bicep`: This is the main Bicep file that describes the desired state of your infrastructure.
  - `mainTerra.tf`: This is the main Terraform file that describes the desired state of your infrastructure.

## Getting Started

1. Clone this repository.
2. Navigate to the `InfrastructureAsCode/` directory.
3. Choose the IaC tool you want to use (Bicep or Terraform) and navigate to the corresponding file (`main.bicep` or `mainTerra.tf`).
4. Follow the instructions in the file to deploy your infrastructure.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details