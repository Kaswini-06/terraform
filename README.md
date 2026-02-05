terraform {
    required_version = "~> 1.14.3" //  Value mention as per your terraform version
    required_providers {
    aws = {
      source  = "hashicorp/aws"
      version = "~> 6.27.0"  // Value mention as per your aws version
     }
    }
   }

provider "aws" {
	region = "us-east-1"
	
}

resource "aws_instance" "aswiniinfra" {
	ami = "ami-068c0051b15cdb816" // Refer aws and get correct ami id
	instance_type = "t3.micro"{
	resource "aws_s3bucket" "aishus3"
	ami = "ami-068c0051b15cdb816"
	instace_type = 't3.micro'
	
}
