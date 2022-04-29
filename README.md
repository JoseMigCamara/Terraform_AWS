# Terraform_AWS
Create an instance with Elastic IP, 2 volumes and security group

## Install AWS CLI 2

## After install AWS
Go to folder .aws

    cd .aws
Change Credentials that you can find on AWS Details

    nano credentials
Go to your folder

    cd ~
    cd Desktop/"name_of_your_folder"
For Initializing Terraform

    terraform init
Generate the config of main.tf

    terraform plan
Apply/Accept create the instance

    terraform apply
Destroy the instance, elastic IP, Security Groups...

    terraform destroy
