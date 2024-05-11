A Terraform module for creating AWS EC2 instance.

Usage
module "ec2_instance" {
  source     = "git::https://github.com/Rajeev-sreedharan/Terraform-Tutorial.git"

  region    = "us-west-2"
}
Inputs
Name	Description	Type	Default	Required
region	AWS region	string	us-east-1	yes
