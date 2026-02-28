...
 # To install Terraform, run these commands

## Required Dependecies

sudo apt update -y
sudo apt install unzip git curl -y

## Install terraform

wget https://releases.hashicorp.com/terraform/1.6.6/terraform_1.6.6_linux_amd64.zip
unzip terraform_1.6.6_linux_amd64.zip
sudo mv terraform /usr/local/bin/
terraform -v


