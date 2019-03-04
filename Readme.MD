# Terraform

## Install on Mac  
You need [Home Brew](https://brew.sh/) to install package
``` bash
brew install awscli
brew install terraform
``` 

## Install on Windows 
 
- Install [AWS CLI](https://docs.aws.amazon.com/cli/latest/userguide/install-windows.html#awscli-install-windows-path)
- Install [Chocolatey](https://chocolatey.org/docs/installation)
- Install Terraform using Chocolatey `choco install terraform -y`
- Install CMDER using Chocolatey `choco install cmdermini -y`
 

## Install on Linux  

``` bash
$sudo apt-get install wget
export VER="0.11.10"
$wget https://releases.hashicorp.com/terraform/${VER}/terraform_${VER}_linux_amd64.zip
$unzip terraform_${VER}_linux_amd64.zip
$sudo mv terraform /usr/local/bin

## Create AzureCLI resources

