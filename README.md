# AWS_VPC

This uses the Scalr service catalog to deploy an AWS VPC

The default values should be updated accordingly:

variable "vpc_cidr" {
 default = "10.2.0.0/24"
}

variable "subnet_cidr1" {
default = "10.2.0.0/28"
}

variable "subnet_cidr2" {
default = "10.2.0.16/28"
}

variable "az1" {
default = "us-east-1a"
}

variable "az2" {
default = "us-east-1b"
}
