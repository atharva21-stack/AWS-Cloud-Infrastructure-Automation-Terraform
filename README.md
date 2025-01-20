
# AWS Cloud Infrastructure Automation Terraform
## Description

This **Terraform project** streamlines the deployment of a fully operational AWS cloud infrastructure. It automates the creation of key components such as Virtual Private Clouds (VPCs), Internet Gateways, Route Tables, Subnets, and Security Groups. Additionally, it includes scripts to automatically associate an Elastic IP with the network interface.

The primary goal is to enable the rapid and hassle-free deployment of an Ubuntu server, complete with Apache2 installation. By automating these processes, the project minimizes manual configuration, ensuring a seamless and efficient setup while reducing the likelihood of errors.
## Table of Contents

- [Getting Started](#Quick-Start)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Terraform Configuration](#installation)

### Prerequisites

List any prerequisites that users need to have in order to use your project. For example:

- **Terraform** (version: 1.5.6)
- **AWS** account with appropriate permissions

## Quick-Start

For a quick start, clone the repository and follow the setup instructions mentioned in the [Installation](#Installation) section of this document. 

---

## Features
- **VPC Setup**: Configuration of a Virtual Private Cloud to facilitate isolated cloud resources.
- **Internet Gateway and Route Tables**: Ensures proper routing of network traffic.
- **Subnet Creation**: Setup of subnets for organizing resources.
- **Security Groups Configuration**: Implementation of security rules for resource access.
- **Elastic IP Attachment**: Automatic attachment of Elastic IP to the network interface.
- **Ubuntu Server Deployment**: Deployment of an Ubuntu server within the configured network.
- **Apache2 Setup**: Installation and configuration of the Apache2 web server on the Ubuntu server.

Whether you are looking to quickly deploy a web server or set up a complex network for your applications on AWS, this Terraform project can be a starting point to automate and streamline the entire process. 

### Installation

Explain how to install your project, including any specific commands or steps. For example:

```bash
# Clone the repository
git clone https://github.com/Nadav23AnT/terraform-infrastructure-automation.git

# Change into the project directory
cd terraform-infrastructure-automation

# Initialize Terraform
╰─ terraform init -backend-config="access_key={your-access-key}" 
                  -backend-config="secret_key={your-secret-key}"

# Apply the configuration
terraform apply
```
