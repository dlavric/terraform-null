# Repository for learning Terraform
This repository is for running Terraform with the `Null provider` for learning purposes

## This Repository creates a Null provider with Terraform

## Instructions

### Prerequisites
- [X] [VirtualBox](https://www.virtualbox.org/wiki/Downloads)

- [X] [Vagrant](https://www.vagrantup.com/downloads)

- [X] [Terraform](https://www.terraform.io/downloads)


## How to Use this Repo

- Clone this repository:
```shell
git clone git@github.com:dlavric/terraform-null.git
```

- Go to the directory where the repo is stored:
```shell
cd terraform-null
```

- Start Vagrant
```shell
vagrant up
```

- Connect to the VM
```
vagrant ssh terraform
```

- Initialize Terraform and apply the changes
```
terraform init
terraform apply
```

- Destroy the Vagrant machine:
```shell
vagrant destroy
```

